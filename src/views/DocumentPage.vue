<template>
  <div>
      <HeaderBar/>
      <div class="container-fluid">
            <FileUploadBox/>
            <AttendeeBox/>
      </div>
  </div>
</template>

<script>
import HeaderBar from '../components/HeaderBar'
import FileUploadBox from '../components/FileUploadBox'
import AttendeeBox from '../components/AttendeeBox'
export default {
    components:{
        HeaderBar,
        FileUploadBox,
        AttendeeBox
    }
}
</script>

<style>

</style>