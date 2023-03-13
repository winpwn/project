<template>
    <div>
        <div>
            <b-navbar class="bv-example-row py-3 navbar-bg text-white">
                <b-col href="#"><b>Succulent Plant Species Checking Application</b></b-col>
                <b-col class="text-right"><b>เกี่ยวกับ</b></b-col>
            </b-navbar>
            <!-- <div class="navbar-container">
            <b-navbar class="bv-example-row py-3  text-dark navbar-componets">
                <b-col href="#"><b>home</b></b-col>
                <b-col class="text-right"><b>เกี่ยวกับ</b></b-col>
            </b-navbar>

        </div> -->
        </div>
        <div class="card-bg-center ">

            <b-card class="card-bg ">
                <div class="row">
                <div class="navbar-container text-dark">
                    <a href=""><b-col><b>home</b></b-col></a>
                    <a href=""><b-col><b>test</b></b-col></a>
                    <a href="" ><b-col><b>เกี่ยวกับ</b></b-col></a>
                    <b-navbar-nav class="input-seach ">
                            <b-nav-form>
                                <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
                                <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
                            </b-nav-form>

                            <!-- <b-nav-item-dropdown text="Lang" right>
                                <b-dropdown-item href="#">EN</b-dropdown-item>
                                <b-dropdown-item href="#">ES</b-dropdown-item>
                            </b-nav-item-dropdown> -->

                    </b-navbar-nav>

                </div>

                </div>

                
            </b-card>
        </div>
        

    </div>
</template>



<style scoped>
.navbar-bg {
    background-color: #1c6758;
}

.card-bg {
    background-color: #3d8361;
    border: solid 2px #d6cda4;
    border-radius: 7px;
    width: 80%;
    display: flex;
    justify-content: center;
}

.card-bg-center {
    display: flex;
    justify-content: center;
}

.navbar-container {
    display: flex;
    /* justify-content: left; */
    /* justify-content: left; */

}

.input-seach {
    margin-left: 1000px;
}

.navbar-container a {
    color: #ffff;
}
</style>