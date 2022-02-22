<template>
  <div class="home">
    <!-- Button trigger modal -->
    <button
      type="button"
      class="btn btn-primary"
      data-bs-toggle="modal"
      data-bs-target="#staticBackdrop"
    >
      Launch static backdrop modal
    </button>

    <!-- Modal -->
    <div
      id="staticBackdrop"
      class="modal fade"
      data-bs-backdrop="static"
      data-bs-keyboard="false"
      tabindex="-1"
      aria-labelledby="staticBackdropLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5
              id="staticBackdropLabel"
              class="modal-title"
            >
              Modal title
            </h5>
            <button
              type="button"
              class="btn-close"
              data-bs-dismiss="modal"
              aria-label="Close"
            />
          </div>
          <div class="modal-body">
            ...
          </div>
          <div class="modal-footer">
            <button
              type="button"
              class="btn btn-secondary"
              data-bs-dismiss="modal"
            >
              Close
            </button>
            <button
              type="button"
              class="btn btn-primary"
            >
              Understood
            </button>
          </div>
        </div>
      </div>
    </div>
    <img
      alt="Vue logo"
      src="../assets/logo.png"
    >
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <button
      type="button"
      class="btn btn-primary"
    >
      Primary
    </button>
    <button
      type="button"
      class="btn btn-secondary"
    >
      Secondary
    </button>
    <button
      type="button"
      class="btn btn-success"
    >
      Success
    </button>
    <button
      type="button"
      class="btn btn-danger"
    >
      Danger
    </button>
    <button
      type="button"
      class="btn btn-warning"
    >
      Warning
    </button>
    <button
      type="button"
      class="btn btn-info"
    >
      Info
    </button>
    <button
      type="button"
      class="btn btn-light"
    >
      Light
    </button>
    <button
      type="button"
      class="btn btn-dark"
    >
      Dark
    </button>

    <button
      type="button"
      class="btn btn-link"
    >
      Link
    </button>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
