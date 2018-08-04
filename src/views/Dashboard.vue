<template>
  <div class="animated fadeIn">
    <b-card no-body class="bg-primary">
      <b-card-body class="pb-0">
        <b-dropdown class="float-right" variant="transparent p-0" right>
          <template slot="button-content">
            <i class="icon-settings"></i>
          </template>
          <b-dropdown-item>Action</b-dropdown-item>
          <b-dropdown-item>Another action</b-dropdown-item>
          <b-dropdown-item>Something else here...</b-dropdown-item>
          <b-dropdown-item disabled>Disabled action</b-dropdown-item>
        </b-dropdown>
        <h4 class="mb-0">9.823</h4>
        <p>Members online</p>
      </b-card-body>
    </b-card>
  </div>
</template>
