<template>
  <div>
    <nav class="navbar navbar-inverse navbar-static-top">
      <div class="container">
        <div class="navbar-header">
          <button
            type="button"
            class="navbar-toggle collapsed"
            data-toggle="collapse"
            data-target="#navbar"
            aria-expanded="false"
            aria-controls="navbar"
          >
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#">وبلاگ</a>
        </div>
        <div id="navbar" class="navbar-collapse collapse">
          <ul class="nav navbar-nav">
            <li class="active">
              <a href="/">خانه</a>
            </li>
            <li>
              <a href="#about">درباره من</a>
            </li>
            <li>
              <a href="#contact">تماس با من</a>
            </li>
            <li class="dropdown">
              <a
                href="#"
                class="dropdown-toggle"
                data-toggle="dropdown"
                role="button"
                aria-haspopup="true"
                aria-expanded="false"
              >
                منوی زیرشاخه ای
                <span class="caret"></span>
              </a>
              <ul class="dropdown-menu">
                <li>
                  <a href="#">اکشن اول</a>
                </li>
                <li>
                  <a href="#">اکشن دوم</a>
                </li>
                <li>
                  <a href="#">اکشن سوم</a>
                </li>
                <li role="separator" class="divider"></li>
                <li class="dropdown-header">منوی ناوبری</li>
                <li>
                  <a href="#">لینک</a>
                </li>
                <li>
                  <a href="#">یک لینک دیگه</a>
                </li>
              </ul>
            </li>
          </ul>
          <ul class="nav navbar-nav navbar-right">
            <li>
              <a href="../navbar/">منوی </a>
            </li>
            <li class="active">
              <a href="./">
                منوی استاتیک
                <span class="sr-only">(منوی کنونی)</span>
              </a>
            </li>
            <li>
              <a href="../navbar-fixed-top/">منوی ثابت</a>
            </li>
          </ul>
        </div>
        <!--/.nav-collapse -->
      </div>
    </nav>

    <section class="banner-section"></section>
    <section class="post-content-section">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 col-md-12 col-sm-12 post-title-block">
            <h1 class="text-center">عنوان مطلب نوشته شده</h1>
            <ul class="list-inline text-center">
              <li>نویسنده | نوسینده وبلاگ</li>
              <li>دسته بندی | دین سیاست فرهنگ اقتصاد</li>
              <li>تاریخ | امروز</li>
            </ul>
          </div>
          <div class="col-lg-9 col-md-9 col-sm-12" style="background-color: white;">
            <p
              class="lead"
            >شسیبشسیبشسیبشسیب شسیب شسی بشسی بش سی بسش یب شس یب شسی بش سیب شس یب شسیب سش یب شسیب شس یب شسیب شس یب شسیب .</p>
            <p>شیسبشسی بشسی ب شسی بشس یب شسی بش سیب شس یبش سیب شسی بش سیب شسی ب شسیب شس یبش سیب شس یبشس یب شسیب شس یب شسیب .</p>
            <div class="well">
              <large>This is image</large>
            </div>
            <p>شسیبشسیبشسیب شسیب شسیبشس یبشسیبشسی بشسیبشسیب شسی بشسیب شسیب شسیبشس یبشسی بشسیب شسیب شسیب شسیب .</p>
            <blockquote>
              <p>شسیبشسی بشسی بش سیب شسیب شس یب شسیب شسی بش سیب شسیب شس یبش سیب .</p>
              <footer>
                شسیبشسیبشسیبشسیبشسیب
                <cite title="Source Title">شسیبشسیبشسیبش</cite>
              </footer>
            </blockquote>
            <p>شسیبشسیبشسیب شسیب شسیبشس یبشسیبشسی بشسیبشسیب شسی بشسیب شسیب شسیبشس یبشسی بشسیب شسیب شسیب شسیب.</p>
            <p>شسیبشسیبشسیب شسیب شسیبشس یبشسیبشسی بشسیبشسیب شسی بشسیب شسیب شسیبشس یبشسی بشسیب شسیب شسیب شسیب.</p>
            <blockquote>
              <p>شسیبشسیبشسیب شسیب شسیبشس یبشسیبشسی بشسیبشسیب شسی بشسیب شسیب شسیبشس یبشسی بشسیب شسیب شسیب شسیب.</p>
            </blockquote>

            <div class="image-block">
              <img
                src="https://static.pexels.com/photos/268455/pexels-photo-268455.jpeg"
                class="img-responsive"
              />
            </div>

            <p>شسیبشسیبشسیب شسیب شسیبشس یبشسیبشسی بشسیبشسیب شسی بشسیب شسیب شسیبشس یبشسی بشسیب شسیب شسیب شسیب.</p>
          </div>
          <div class="col-lg-3 col-md-3 col-sm-12">
            <div class="well">
              <h2>عضویت در خبرنامه این وبلاگ</h2>
              <p>توضیحات فرم</p>
              <div class="input-group">
                <input type="text" class="form-control" placeholder="Search for..." />
                <span class="input-group-btn">
                  <button class="btn btn-default" type="button">Go!</button>
                </span>
              </div>
            </div>
            <div class="well">
              <h2>به اشتراک گذاری</h2>
              <ul class="list-inline">
                <li>
                  <span class="glyphicon glyphicon-heart" aria-hidden="true"></span>
                </li>
                <li>
                  <span class="glyphicon glyphicon-heart" aria-hidden="true"></span>
                </li>
                <li>
                  <span class="glyphicon glyphicon-heart" aria-hidden="true"></span>
                </li>
                <li>
                  <span class="glyphicon glyphicon-heart" aria-hidden="true"></span>
                </li>
              </ul>
            </div>
            <div class="well">
              <h2>درباره نویسنده</h2>
              <img src class="img-rounded" />
              <p>شسیبشسیبشسیب شسیب شسیبشس یبشسیبشسی بشسیبشسیب شسی بشسیب شسیب شسیبشس یبشسی بشسیب شسیب شسیب شسیب</p>
              <a href="#" class="btn btn-default">مطالعه بیشتر</a>
            </div>
            <div class="list-group">
              <a class="list-group-item active" href="#">
                <h4 class="list-group-item-heading">لیست گروپ هدینگ</h4>
                <p
                  class="list-group-item-text"
                >شسیبشسیبشسیب شسیب شسیبشس یبشسیبشسی بشسیبشسیب شسی بشسیب شسیب شسیبشس یبشسی بشسیب شسیب شسیب شسیب.</p>
              </a>
              <a class="list-group-item" href="#">
                <h4 class="list-group-item-heading">لیست گروپ هدینگ</h4>
                <p
                  class="list-group-item-text"
                >شسیبشسیبشسیب شسیب شسیبشس یبشسیبشسی بشسیبشسیب شسی بشسیب شسیب شسیبشس یبشسی بشسیب شسیب شسیب شسیب.</p>
              </a>
              <a class="list-group-item" href="#">
                <h4 class="list-group-item-heading">لیست گروپ هدینگ</h4>
                <p
                  class="list-group-item-text"
                >شسیبشسیبشسیب شسیب شسیبشس یبشسیبشسی بشسیبشسیب شسی بشسیب شسیب شسیبشس یبشسی بشسیب شسیب شسیب شسیب.</p>
              </a>
            </div>
            <div class="well">
              <div class="media">
                <div class="media-left">
                  <a href="#">
                    <img
                      data-src="holder.js/64x64"
                      class="media-object"
                      alt="64x64"
                      style="width: 64px; height: 64px;"
                      src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiIHN0YW5kYWxvbmU9InllcyI/PjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iNjQiIGhlaWdodD0iNjQiIHZpZXdCb3g9IjAgMCA2NCA2NCIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+PCEtLQpTb3VyY2UgVVJMOiBob2xkZXIuanMvNjR4NjQKQ3JlYXRlZCB3aXRoIEhvbGRlci5qcyAyLjYuMC4KTGVhcm4gbW9yZSBhdCBodHRwOi8vaG9sZGVyanMuY29tCihjKSAyMDEyLTIwMTUgSXZhbiBNYWxvcGluc2t5IC0gaHR0cDovL2ltc2t5LmNvCi0tPjxkZWZzPjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+PCFbQ0RBVEFbI2hvbGRlcl8xNTY5MjIxZTM1NSB0ZXh0IHsgZmlsbDojQUFBQUFBO2ZvbnQtd2VpZ2h0OmJvbGQ7Zm9udC1mYW1pbHk6QXJpYWwsIEhlbHZldGljYSwgT3BlbiBTYW5zLCBzYW5zLXNlcmlmLCBtb25vc3BhY2U7Zm9udC1zaXplOjEwcHQgfSBdXT48L3N0eWxlPjwvZGVmcz48ZyBpZD0iaG9sZGVyXzE1NjkyMjFlMzU1Ij48cmVjdCB3aWR0aD0iNjQiIGhlaWdodD0iNjQiIGZpbGw9IiNFRUVFRUUiLz48Zz48dGV4dCB4PSIxMi41IiB5PSIzNi44Ij42NHg2NDwvdGV4dD48L2c+PC9nPjwvc3ZnPg=="
                      data-holder-rendered="true"
                    />
                  </a>
                </div>
                <div class="media-body">
                  <h4 class="media-heading">مدیا</h4>شیسبشسیبشسیبشسیب.
                </div>
              </div>
              <div class="media">
                <div class="media-left">
                  <a href="#">
                    <img
                      data-src="holder.js/64x64"
                      class="media-object"
                      alt="64x64"
                      style="width: 64px; height: 64px;"
                      src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiIHN0YW5kYWxvbmU9InllcyI/PjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iNjQiIGhlaWdodD0iNjQiIHZpZXdCb3g9IjAgMCA2NCA2NCIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+PCEtLQpTb3VyY2UgVVJMOiBob2xkZXIuanMvNjR4NjQKQ3JlYXRlZCB3aXRoIEhvbGRlci5qcyAyLjYuMC4KTGVhcm4gbW9yZSBhdCBodHRwOi8vaG9sZGVyanMuY29tCihjKSAyMDEyLTIwMTUgSXZhbiBNYWxvcGluc2t5IC0gaHR0cDovL2ltc2t5LmNvCi0tPjxkZWZzPjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+PCFbQ0RBVEFbI2hvbGRlcl8xNTY5MjIxZTM1NSB0ZXh0IHsgZmlsbDojQUFBQUFBO2ZvbnQtd2VpZ2h0OmJvbGQ7Zm9udC1mYW1pbHk6QXJpYWwsIEhlbHZldGljYSwgT3BlbiBTYW5zLCBzYW5zLXNlcmlmLCBtb25vc3BhY2U7Zm9udC1zaXplOjEwcHQgfSBdXT48L3N0eWxlPjwvZGVmcz48ZyBpZD0iaG9sZGVyXzE1NjkyMjFlMzU1Ij48cmVjdCB3aWR0aD0iNjQiIGhlaWdodD0iNjQiIGZpbGw9IiNFRUVFRUUiLz48Zz48dGV4dCB4PSIxMi41IiB5PSIzNi44Ij42NHg2NDwvdGV4dD48L2c+PC9nPjwvc3ZnPg=="
                      data-holder-rendered="true"
                    />
                  </a>
                </div>
                <div class="media-body">
                  <h4 class="media-heading">شسیبشیسب</h4>شیبشسیبشسیبشسیبشسیبشسیبسشیب.
                </div>
              </div>
              <div class="media">
                <div class="media-left">
                  <a href="#">
                    <img
                      data-src="holder.js/64x64"
                      class="media-object"
                      alt="64x64"
                      style="width: 64px; height: 64px;"
                      src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiIHN0YW5kYWxvbmU9InllcyI/PjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iNjQiIGhlaWdodD0iNjQiIHZpZXdCb3g9IjAgMCA2NCA2NCIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+PCEtLQpTb3VyY2UgVVJMOiBob2xkZXIuanMvNjR4NjQKQ3JlYXRlZCB3aXRoIEhvbGRlci5qcyAyLjYuMC4KTGVhcm4gbW9yZSBhdCBodHRwOi8vaG9sZGVyanMuY29tCihjKSAyMDEyLTIwMTUgSXZhbiBNYWxvcGluc2t5IC0gaHR0cDovL2ltc2t5LmNvCi0tPjxkZWZzPjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+PCFbQ0RBVEFbI2hvbGRlcl8xNTY5MjIxZTM1NSB0ZXh0IHsgZmlsbDojQUFBQUFBO2ZvbnQtd2VpZ2h0OmJvbGQ7Zm9udC1mYW1pbHk6QXJpYWwsIEhlbHZldGljYSwgT3BlbiBTYW5zLCBzYW5zLXNlcmlmLCBtb25vc3BhY2U7Zm9udC1zaXplOjEwcHQgfSBdXT48L3N0eWxlPjwvZGVmcz48ZyBpZD0iaG9sZGVyXzE1NjkyMjFlMzU1Ij48cmVjdCB3aWR0aD0iNjQiIGhlaWdodD0iNjQiIGZpbGw9IiNFRUVFRUUiLz48Zz48dGV4dCB4PSIxMi41IiB5PSIzNi44Ij42NHg2NDwvdGV4dD48L2c+PC9nPjwvc3ZnPg=="
                      data-holder-rendered="true"
                    />
                  </a>
                </div>
                <div class="media-body">
                  <h4 class="media-heading">لسیبلسیبل</h4>شیبشسیبشسیبشسیبشسیبشسیبسشیب.
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- /container -->
    </section>

    <section class="footer-link">
      <a href="http://bootsnipp.com/grafreez" target="_blank">شسیبشسیبشسیب</a>
    </section>
  </div>
</template>
 
<script>
export default {
  data() {
    return {
      url: "",
      pics: [],
      sokhanrans: [],
      isLoad: false
    };
  },
  created() {
    this.urlInit();
    this.getSokhanran();
    this.isLoggedIn();
  },
  methods: {
    urlInit() {
      this.url = process.env.MIX_API_URL
        ? process.env.MIX_API_URL
        : "";
    },
    isLoggedIn() {
      if (localStorage.getItem("jwt")) {
        this.loginText = "پروفایل";
        //setValue('reg','محیط کاربری');
      } else {
        //setValue('reg','ثبت نام');
        this.loginText = "ورود/ثبت نام";
      }
    },
    getInit() {
      this.isLoad = false;
      let uri = `/api/v1/sokhanran`;
      console.log(uri);
      this.axios
        .get(uri)
        .then(response => {
          console.log(response);
          let g = response.data[0].pictures;
          g.forEach(function(part, index) {
            this[index] = "uploads/" + this[index];
          }, g); // use arr as this
          this.pics = g;
          console.log(this.gallery);
          this.isLoad = true;
        })
        .catch(error => {
          console.log("Error pageValues get init sokhanranComponent");
          console.log(error);
        });
    },
    getSokhanran() {
      this.isLoad = false;
      let uri = `/api/v1/sokhanran`;
      console.log(uri);
      this.axios
        .get(uri)
        .then(response => {
          console.log(response);
          this.sokhanrans = response.data.data;

          this.sokhanrans.forEach(function(part, index) {
            if (this[index].profile_picture)
              this[index].img =
                "/images/avatars/" + this[index].profile_picture;
            else this[index].img = "/images/noimage.png";

            this[index].link = "/p/" + this[index].id;
          }, this.sokhanrans);

          console.log("sokhanran");
          console.log(this.sokhanrans);

          this.isLoad = true;
        })
        .catch(error => {
          console.log("Error sokhanrans");
          console.log(error);
        });
    }
  }
};
</script>
 
<style>
.navbar{margin-bottom:0;}
section{width:100%; float:left;}
.banner-section{background-image:url("https://static.pexels.com/photos/373912/pexels-photo-373912.jpeg"); background-size:cover; height: 380px; left: 0; position: absolute; top: 0; background-position:0;}
.post-title-block{padding:100px 0;}
.post-title-block h1 {color: #fff; font-size: 85px; font-weight: bold; text-transform: capitalize;}
.post-title-block li{font-size:20px; color: #fff;}
.image-block{float:left; width:100%; margin-bottom:10px;}
.footer-link{float:left; width:100%; background:#222222; text-align:center; padding:30px;}
.footer-link a{color:#A9FD00; font-size:18px; text-transform:uppercase;}
</style>

<style lang="scss">
</style>