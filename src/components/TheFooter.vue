<template>
    <div>
 <div class="footer">
      <span class="left-circle">
        <img src="@/assets/images/qustion.png">
      </span>
      <span class="sitename">All Rights reserved for yamiyami.de</span>
      <span class="right-circle">
        <img src="@/assets/images/multiple.png">
      </span>
    </div>
    <div class="lang-sec">
      <p class="lang-head">Select your Favorite Language</p>
      <div class="lag-box">
        <div class="lang">
          <div class="flag">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              width="85px"
              height="57px"
            >
              <image
                x="0px"
                y="0px"
                width="85px"
                height="57px"
                xlink:href="data:img/png;base64,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"
              ></image>
            </svg>
          </div>
          <p class="l-name">Turkce</p>
        </div>
        <div class="lang">
          <div class="flag">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              width="85px"
              height="56px"
            >
              <image
                x="0px"
                y="0px"
                width="85px"
                height="56px"
                xlink:href="data:img/png;base64,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"
              ></image>
            </svg>
          </div>
          <p class="l-name">English</p>
        </div>
        <div class="lang">
          <div class="flag">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              width="85px"
              height="56px"
            >
              <path
                fill-rule="evenodd"
                fill="rgb(0, 0, 0)"
                d="M0.000,0.000 L85.000,0.000 L85.000,18.712 L0.000,18.712 L0.000,0.000 Z"
              ></path>
              <path
                fill-rule="evenodd"
                fill="rgb(216, 0, 39)"
                d="M0.000,18.577 L85.000,18.577 L85.000,37.288 L0.000,37.288 L0.000,18.577 Z"
              ></path>
              <path
                fill-rule="evenodd"
                fill="rgb(255, 218, 68)"
                d="M0.000,37.288 L85.000,37.288 L85.000,56.000 L0.000,56.000 L0.000,37.288 Z"
              ></path>
            </svg>
          </div>
          <p class="l-name">Deutsch</p>
        </div>
        <div class="lang">
          <div class="flag">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              width="85px"
              height="57px"
            >
              <image
                x="0px"
                y="0px"
                width="85px"
                height="57px"
                xlink:href="data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFUAAAA5CAMAAABwHZdJAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAQlBMVEXYACfYACfYACfXACbdHCv+1EP/3ET/2kT/40X3rD7YACfYACfYACfYACfXACbdHCv+1EP/3ET/2kT/40X3rD7////b1ElrAAAADXRSTlPc7fHt7e3t7e3t+qGtygFISQAAAAFiS0dEFeXY+aMAAAAHdElNRQfjAgITMRhHnNqqAAAAX0lEQVRYw+3WxxHAQBACQc47eSn/WJUE+9gqJoD+AhD4AXHnFxEM1CBVqlSprtR08EvIJ7+McvErqDe/ivbwa1KlSpXqSu0vv47x8RtGa+jpD0iVKlWqJ3UaqBNr47d+KqENu19gVq8AAAAASUVORK5CYII="
              ></image>
            </svg>
          </div>
          <p class="l-name">Spanish</p>
        </div>
      </div>
    </div>


    </div>
</template>

<script>
export default {

}
</script>

<style scoped>

.footer {position: fixed;height: 45px;background: #ffffff;width: 100%;bottom: 0;text-align: center;font-weight: 700;padding: 12px 0;box-sizing: border-box;color: #424242;}
.sitename {font-size: 14px;}
.left-circle {width: 30px;height: 30px;float: left;margin-left: 20px;border-radius: 50%;overflow: hidden;margin-top: -4px;}
.left-circle img {width: 100%;float: left;}
.right-circle {width: 30px;height: 30px;float: right;margin-right: 20px;border-radius: 50%;overflow: hidden;margin-top: -4px;cursor: pointer;}
.right-circle img {width: 100%;float: left;}



/*-----------popup-----------*/

.lang-sec {display: none;position: absolute;width: 700px;height: auto;background: #fff;top: 50%;left: 50%;transform: translate(-50%, -50%);box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.22);z-index: 99;}
.lang-head {font-size: 14px;font-weight: 550;color: #424242;text-align: center;border-bottom: 1px solid #d3d3d3;margin: 0;padding: 15px;box-sizing: border-box;}
.lag-box {width: 100%;float: left;padding: 20px;box-sizing: border-box;}
.lang {width: calc(50% - 24px);height: 150px;margin: 10px;float: left;border-radius: 5px;border: 1px solid #d3d3d3;cursor: pointer;}
.lang:hover {background: #749f01;transition: 0.3s ease;}
.flag {width: 100%;text-align: center;padding: 25px;box-sizing: border-box;padding-bottom: 0px;}
.lang p {font-weight: 700;text-align: center;color: #424242;}
.lang:hover p {color: #fff;}


</style>
