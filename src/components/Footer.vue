<template>
    <div>
        <v-card width="100%" height="200px" class="main-footer">

            <div class="row">
                <div class="col">
                    <p class="text-monospace" >Company :  xxx</p>
                    <p class="text-monospace" >Company :  xxx</p>
                </div> 
                 <div class="col">
                    <p class="text-monospace" >Company :  xxx</p>
                    <p class="text-monospace" >Company :  xxx</p>

                </div> 
                 <div class="col">
                    <p class="text-monospace" >Company :  xxx</p>
                    <p class="text-monospace" >Company :  xxx</p>
  
                </div> 
                <div class="col">
                    <p class="text-monospace" >Company :  xxx</p>
                    <p class="text-monospace" >Company :  xxx</p>
                </div> 
                <div class="col">
                    <p class="text-monospace" >Company :  xxx</p>
                    <p class="text-monospace" >Company :  xxx</p>
                </div> 
            </div>
           

            <v-col class>
                 <div class="d-flex mt-12">
                    <v-img
                    alt="DBD Logo"
                    class="shrink"
                    contain
                    src="image/dbd.png"
                    transition="scale-transition"
                    width="75"
                    />
                </div>
            </v-col>


            
            <v-col class>
                <div class="d-flex flex-row-reverse left-pic mr-3">
                    <v-img
                    alt="AIA Logo"
                    class="shrink"
                    contain
                    src="image/aia.png"
                    transition="scale-transition"
                    width="55"
                    />

                    <v-img
                    alt="THAPRA Logo"
                    class="shrink"
                    contain
                    src="image/thaipra.png"
                    transition="scale-transition"
                    width="90"
                    />

                    <v-img
                    alt="THAIVIVAT Logo"
                    class="shrink"
                    contain
                    src="image/thaivivat.png"
                    transition="scale-transition"
                    width="55"
                    />

                    <v-img
                    alt="MEUNG Logo"
                    class="shrink"
                    contain
                    src="image/mueng.png"
                    transition="scale-transition"
                    width="55"
                    />
                </div>
            </v-col>
           

        </v-card>


        <v-footer dark padless>
            <v-col
                class="text-center"
                cols="12"
                dark
                >
                {{ new Date().getFullYear() }} <strong>COPYRIGHT OKLIFE </strong>
            </v-col>
        </v-footer>

    </div>

    
</template>
<script>
export default {
    name:"Footer",
    data:()=>{

    }
}
</script>
<style>
.main-footer{
    background: linear-gradient(180deg, rgba(255, 255, 255, 0.75) 0%, rgba(255, 255, 255, 0) 100%), linear-gradient(135deg, #71F8D7 0%, #90F7EC 59.9%, #13C8B4 100%);
}

.left-pic {
  position: absolute;
  top: 170px;
  left: 1200px;
  z-index: 1;
  float: right;
}

</style>
