<script>
	let name = "Welcome To INOLINX , this is a Best Chance for improvment";
	let src = "image/inolinx.jpg";
	let text = "Hi Friend This is commiuty bussinese Website for find a job suation where you are live at iran . you can learn everythings you want to do ,but cosider make you as strong man . it is something you want to do just like that .Allright Good Liuck my friend .Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem officia cupiditate pariatur suscipit temporibus optio hic eveniet. Omnis, ab quis. Assumenda velit ratione esse distinctio voluptate cumque fugiat. Molestias, quis? Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem officia cupiditate pariatur suscipit temporibus optio hic eveniet. Omnis, ab quis. Assumenda velit ratione esse distinctio voluptate cumque fugiat. Molestias, quis? Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem officia cupiditate pariatur suscipit temporibus optio hic eveniet. Omnis, ab quis. Assumenda velit ratione esse distinctio voluptate cumque fugiat. Molestias, quis? Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem officia cupiditate pariatur suscipit temporibus optio hic eveniet. Omnis, ab quis. Assumenda velit ratione esse distinctio voluptate cumque fugiat. Molestias, quis? Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem officia cupiditate pariatur suscipit temporibus optio hic eveniet. Omnis, ab quis. Assumenda velit ratione esse distinctio voluptate cumque fugiat. Molestias, quis? Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem officia cupiditate pariatur suscipit temporibus optio hic eveniet. Omnis, ab quis. Assumenda velit ratione esse distinctio voluptate cumque fugiat. Molestias, quis? Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem officia . <br> Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem officia cupiditate pariatur suscipit temporibus optio hic eveniet. Omnis, ab quis. Assumenda velit ratione esse distinctio voluptate cumque fugiat. Molestias, quis?";
    export let searchTerm;
    export let Pic;
    export let introText;
    export let Time;
</script>
<style lang="scss">
    .col-12{
        overflow: hidden;
        position: relative;
        
        img{
            cursor: pointer;
            opacity: 1;
            transition: all 0.6s;
            margin:0px 6px 0 0;
            border: 1px solid gray;
        }
        img:hover{
            opacity: 0.7;
            transform: scale(1.1,1.1) ;
        }
    }
    .col-12{
        .col-12{
            font-style: italic;
            color: dimgrey;
            font-size: 12px;
        }
    }
    .col-11{
        hr{
            background-color: black;
        }
        .col-12{
            p{
                font-size: 15px;
            }
        }
    }
    .cust-icon{
        color: black;
        font-size: 20px;
        transition: all 0.5s;
    }
    .cust-icon:hover{
        opacity: 0.4;
        
    }
</style>
<div class="row align-content-around">
    <div class="col-12 col-md-10 mx-auto">
        <div class=" my-3">
            <img class="w-100 " src="{src}" alt="{`photo of ${src}`}">
        </div>
        <!-- svelte-ignore a11y-invalid-attribute -->
        <a href="#">
            <h2 class="artist-name mb-0">{name}</h2>
        </a>
        <div class="container">
            <div class="row">
                <div class="col-11 col-md-10 ">
                    <div class="col-12">
                        <div class="col-12 my-2" style="overflow: hidden;position: relative;">
                            <img class="rounded-circle" style="width: 50px;height: 50px;" src="{Pic}" alt="{`picture of produce owner ${searchTerm}`}">
                            <i class="fas fa-user-edit"></i> &nbsp;{searchTerm} &nbsp;&nbsp; &nbsp;  <i class="fas fa-clock"></i> &nbsp; {Time}
                        </div>
                    </div>
                    <!--<div class="col-12">
                        <p class="my-1 ms-5">
                            {introText}
                        </p>
                    </div> -->
                </div>
            </div>
        </div>
        <hr class="my-1 w-auto ">
        <p class="my-3" style="text-align: justify;">{text}</p>
        <br><hr class="my-1 w-auto ">
        <div class=" mt-3">
            <i class="fas fa-link"></i> Share : &nbsp;&nbsp;&nbsp; 
            <a href="" class="cust-icon"><i class=" fab fa-github fa-lg"></i></a>&nbsp; &nbsp; 
            <a href="" class="cust-icon"><i class=" fab fa-twitter fa-lg"></i></a>&nbsp; &nbsp; 
            <a href="" class="cust-icon"><i class=" fas fa-check-circle fa-lg"></i></a>&nbsp; &nbsp; 
            <a href="" class="cust-icon"><i class=" fab fa-instagram fa-lg"></i></a>&nbsp; &nbsp; 
        </div>
    </div>
</div>


