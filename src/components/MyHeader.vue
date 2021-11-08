<template>
  <div>
    <div class="app">
      <div class="myheader">
        <img src="../assets/images/1_56.gif" alt="" />
      </div>
      <div class="tags">
        <div class="hot_img">
          <img src="../assets/images/1_59.gif" alt="" />
        </div>

        <div class="hot_img">
          <img src="../assets/images/1_72.gif" alt="" />
        </div>

        <div class="hot_img">
          <img src="../assets/images/1_71.gif" alt="" />
        </div>

        <div class="hot_img">
          <img src="../assets/images/1_68.gif" alt="" />
        </div>

        <div class="hot_img">
          <img src="../assets/images/1_66.gif" alt="" />
        </div>

        <div class="hot_img">
          <img src="../assets/images/1_62.gif" alt="" />
        </div>

        <div class="hot_img">
          <img src="../assets/images/1_59.gif" alt="" />
        </div>

        <div class="hot_img">
          <p>查看更多>></p>
        </div>
      </div>
    </div>
    <div class="box">
      <div class="myheader">
        <img src="../assets/images/1_78.gif" alt="" />
      </div>
      <div class="list">
        <ul>
          <li>
            <span class="price">1、39岁的小伙子,就发生了发颤,怎...</span>

            <span class="text">2021.10.15</span>
          </li>
          <li>
            <span class="price">2、市北市民留言咨询这些问题,官...</span>

            <span class="text">2021.10.15</span>
          </li>
          <li>
            <span class="price">3、美供应链受阻问题雪上加霜</span>
            <span class="text">2021.10.15</span>
          </li>
          <li>
            <span class="price">4、篮网有能力解决他们的问题度...</span>
            <span class="text">2021.10.15</span>
          </li>
          <li>
            <span class="price">5、记者实测快递企业智能客服:回...</span>
            <span class="text">2021.10.15</span>
          </li>
          <li>
            <span class="price">6、养老金有哪些渠道可以获得?有...</span>
            <span class="text">2021.10.15</span>
          </li>
          <li>
            <span class="price">7、怎么样买保险才是最合理的?咱...</span>
            <span class="text">2021.10.15</span>
          </li>
          <li>
            <span class="price">8、全面建成小康社会的重要举措...</span>
            <span class="text">2021.10.15</span>
          </li>
          <li>
            <span class="price">9、摩根士丹利重磅报告:中国经济...</span>
            <span class="text">2021.10.15</span>
          </li>
        </ul>
        <div class="sousuo">
          <span>查看更多资讯</span><img src="../assets/images/ss.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "MyHeader",
};
</script>
<style scoped lang="scss">
.app {
  width: 3.56rem;
  height: 4.07rem;
  margin: 0 auto;
  border-radius: 0.05rem;
  .myheader {
    width: 3.55rem;
    height: 0.55rem;
    background: #ffffff;
    padding-bottom: 0.05rem;
    img {
      width: 100%;
      height: 0.55rem;
      float: left;
      border-radius: 0.04rem;
    }
  }
  .tags {
    width: 3.55rem;
    height: 3.52rem;
    background: #ffffff;
    border-radius: 0.05rem;

    .hot_img {
      width: 171px;
      height: 75px;
      background-color: #ffffff;
      border-radius: 3px;
      float: left;
      margin: 0.05rem 0.03rem;
      img {
        width: 171px;
        height: 75px;
        background-color: #a7a7a7;
        border-radius: 3px;
      }
      p {
        text-align: center;
        line-height: 0.75rem;
        color: #ffffff;
        font-size: 0.17rem;
        background: #d4d4d4;
        border-radius: 3px;
      }
    }
  }
}
.box {
  width: 3.56rem;
  height: 4.7rem;
  margin: 0 auto;
  border-radius: 0.05rem;
  margin-top: 0.15rem;
  background: #ffffff;
  .myheader {
    width: 3.55rem;
    height: 0.55rem;
    background: #ffffff;
    border-radius: 0.05rem;
    padding-bottom: 0.05rem;
    img {
      width: 100%;
      height: 0.55rem;
      float: left;
      border-radius: 0.04rem;
    }
  }
  .list {
    height: 3.9rem;
    ul {
      li {
        border-bottom: 0.01rem solid #ccc;
        margin-top: 0.2rem;
        display: flex;
        justify-content: space-between;
        .price {
          width: 2.4rem;
          height: 0.15rem;
          font-family: PingFang-SC-Medium;
          font-size: 15px;
          font-weight: normal;
          font-stretch: normal;
          line-height: 12px;
          letter-spacing: 0px;
          text-align: left;
          color: #333333;
        }
        .text {
          width: 74px;
          height: 11px;
          font-family: PingFang-SC-Medium;
          font-size: 14px;
          font-weight: normal;
          font-stretch: normal;
          line-height: 12px;
          letter-spacing: 0px;
          color: #999999;
          margin-left: 0.4rem;
        }
      }
    }
    .sousuo {
      width: 3.31rem;
      height: 0.44rem;
      background-color: #3f555f;
      border-radius: 0.05rem;
      border: solid 0.01rem #1776af;
      margin-left: 0.12rem;
      margin-top: 0.15rem;
      text-align: center;
      line-height: 0.44rem;
      position: relative;
      span {
        width: 0.95rem;
        height: 0.15rem;
        font-family: PingFang-SC-Medium;
        font-size: 0.16rem;
        font-weight: normal;
        letter-spacing: 0px;
        color: #ffffff;
      }
      img {
        width: 0.16rem;
        height: 0.16rem;
        position: absolute;
        top: 0.14rem;
      }
    }
    .sousuo:hover {
      background: #ffffff;

      border: 0.01rem solid #1776af;
      span:hover {
        color: #3f555f;
      }
    }
  }
}
</style>
