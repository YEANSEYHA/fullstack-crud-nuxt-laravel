<template>
  <v-simple-table>
    <template v-slot:default>
      <thead>
        <tr>
          <th class="text-right">
            Name
          </th>
          <th class="text-left">
            Email
          </th>
          <th class="text-left">
            Phone
          </th>
          <th class="text-left">
            Action
          </th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Name</td>
          <td>Email</td>
          <td>data</td>
          <td>
              <v-btn color="red" elevation="11" small>Delete</v-btn>
              <v-btn color="yellow" elevation="11" small>Update</v-btn>
          </td>
        </tr>
      </tbody>
    </template>
  </v-simple-table>
</template>

<script>

</script>

<style>


</style>