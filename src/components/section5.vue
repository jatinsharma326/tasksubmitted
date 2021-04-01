<template>
   <section>
  <div class="container">
    <div class="row">
      <div class="col-md-12">
  <div class="row d-flex justify-content-center mt-100 mb-100">
        <div class="card">
            <div class="card-body text-center">
                <h4 class="card-title" style="text-align: left;">Reviews </h4>
            </div>
            <div class="comment-widgets">
                <div class="d-flex flex-row comment-row m-t-0">
                    <div class="p-2"><img src="https://res.cloudinary.com/dxfq3iotg/image/upload/v1574583336/AAA/4.jpg" alt="user" width="50" class="rounded-circle"></div>
                    <div class="comment-text w-100">
                        <h6 class="font-medium">Ankit Jain &nbsp;&nbsp;&nbsp; <span style="color: #A1A1A1;font-size: 0.5rem;"> November 20, 2020 AT 11:23 AM</span> </h6> <span class="m-b-15 d-block">This is awesome website. I would love to comeback again. </span>
                    </div>
                </div> 
                <div class="d-flex flex-row comment-row">
                    <div class="p-2"><img src="https://res.cloudinary.com/dxfq3iotg/image/upload/v1574583319/AAA/3.jpg" alt="user" width="50" class="rounded-circle"></div>
                    <div class="comment-text active w-100">
                        <h6 class="font-medium">Michael Hussey  &nbsp;&nbsp;&nbsp; <span style="color: #A1A1A1;font-size: 0.5rem;"> November 20, 2020 AT 11:23 AM</span></h6> <span class="m-b-15 d-block">Thanks .com for providing such useful snippets. </span>
                    </div>
                </div> 
                <div class="d-flex flex-row comment-row">
                    <div class="p-2"><img src="https://res.cloudinary.com/dxfq3iotg/image/upload/v1574583246/AAA/2.jpg" alt="user" width="50" class="rounded-circle"></div>
                    <div class="comment-text w-100">
                        <h6 class="font-medium">Johnathan Doeting   &nbsp;&nbsp;&nbsp; <span style="color: #A1A1A1;font-size: 0.5rem;"> November 20, 2020 AT 11:23 AM</span></h6> <span class="m-b-15 d-block">Great industry leaders are not the real heroes of stock market. </span>
                    </div>
                </div>
            </div> 
            <div class="d-grid gap-2">
             <button class="btn border border-danger"  type="button" style="color: red;">Reviews</button>
            </div>
        </div>
  </div>
  </div>
</div>
</div>
  <br />
  
</section>
</template>
<style scoped>


.one{
    width:100%;
    height: 100%;
}
.comment-widgets {
    position: relative;
    margin-bottom: 10px
}

.comment-widgets .comment-row {
    border-bottom: 1px solid transparent;
    padding: 14px;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    margin: 10px 0
}

.p-2 {
    padding: 0.5rem !important
}

.comment-text {
    padding-left: 15px
}

.w-100 {
    width: 100% !important
}

.m-b-15 {
    margin-bottom: 15px
}

.btn-sm {
    padding: 0.25rem 0.5rem;
    font-size: 0.76563rem;
    line-height: 1.5;
    border-radius: 1px
}
.btn-cyan {
    color: #fff;
    background-color: #27a9e3;
    border-color: #27a9e3
}

.btn-cyan:hover {
    color: #fff;
    background-color: #1a93ca;
    border-color: #198bbe
}

.comment-widgets .comment-row:hover {
    background: rgba(0, 0, 0, 0.05)
}
.everyhor{
    color:rgb(255, 0, 0);
    width:20%
}

</style>
<script>

export default ({
   name:'section5'
})
</script>
