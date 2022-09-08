<template>
  <div>
    <div class="story-div">
       <story-view :storyLink="`https://scontent.fccu20-1.fna.fbcdn.net/v/t1.6435-9/145143874_1062578930903927_6526828013676758269_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=174925&_nc_ohc=lQO66xe59xkAX9EKm1n&_nc_ht=scontent.fccu20-1.fna&oh=00_AT9mjgvZ0uA8YtVR-LNhiy3T2G7ushWWc3mh2nn3VSZx3w&oe=6340EFA4`" :storyName="`Zay_Nick`"/>
       <story-view :storyLink="`https://scontent.fccu20-1.fna.fbcdn.net/v/t39.30808-1/255334260_1252230451957947_8721847696695125402_n.jpg?stp=dst-jpg_p320x320&_nc_cat=102&ccb=1-7&_nc_sid=7206a8&_nc_ohc=dIk6vm8CGtYAX_iwquR&_nc_ht=scontent.fccu20-1.fna&oh=00_AT9gX6GutFnFM-rGJEGe-6Cz7IQxc9KxvgzaCysR_QVKCA&oe=631F329E`" :storyName="`Roh_Hann`"/>
       <story-view :storyLink="`https://scontent.fccu20-1.fna.fbcdn.net/v/t1.6435-9/110046320_954201841672586_7108805876025552553_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=174925&_nc_ohc=RDX_X19Pd9MAX8cBgXu&tn=Z0jYfRH9dBmlaux6&_nc_ht=scontent.fccu20-1.fna&oh=00_AT9ZSEpbBCihyRxpTO4mp6V898Goam2X4AS6wLTx8hyKsQ&oe=633E67BE`" :storyName="`Todi Anant`"/>
       <story-view :storyLink="`https://scontent.fccu20-1.fna.fbcdn.net/v/t39.30808-6/239889008_956305918254024_6056205359829913636_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=8bfeb9&_nc_ohc=yrcM9g5w6fkAX__zMY6&_nc_ht=scontent.fccu20-1.fna&oh=00_AT-s4D-QUhDl0pdLfi-QF1wqdGQLdmNotuoFU5gfqwna9g&oe=631E4A27`" :storyName="`Nitesh_M..`"/>
       <story-view :storyLink="`https://scontent.fccu20-1.fna.fbcdn.net/v/t1.6435-9/61830368_601337907014814_2509081892452564992_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=e3f864&_nc_ohc=u6MG-EV9XVoAX_cinEH&_nc_ht=scontent.fccu20-1.fna&oh=00_AT_O6hTPubvTk0WAcopSGppFiqLnkwT2F4OsD8tKxR147g&oe=633ED8A8`" :storyName="`Sujal Niroula`"/>
    </div>
  </div>
</template>

<script>
    import StoryView from '@/components/StoryView.vue'
export default {
  name: "StoryComponent",
  components : {StoryView}
};
</script>

<style>
.post-section {
  width: 470px;
  height: 100vh;
  /* background-color: red; */
  margin-left: 23%;
  padding-top: 26px;
}
.story-div {
  width: 100%;
  height: 117px;
  background-color: white;
  border-radius: 6px;
  border: 1px solid #dbdada;
  padding-top: 14px;
}
.story-div-bg {
  width: 70px;
  height: 70px;
  background: rgb(255, 195, 0);
  background: linear-gradient(
    90deg,
    rgba(255, 195, 0, 1) 0%,
    rgba(255, 102, 42, 1) 29%,
    rgba(242, 3, 132, 1) 55%,
    rgba(255, 88, 153, 1) 87%
  );
  border-radius: 50%;
  position: relative;
}
.story-img-bg {
  height: 64px;
  width: 64px;
  background-color: white;
  border-radius: 50%;
  position: absolute;
  left: 2.8px;
  top: 2.8px;
}
.story-profile {
  width: 58px;
  height: 59px;
  border-radius: 50%;
  position: absolute;
  left: 2.5px;
  top: 2.5px;
  object-fit: cover;
}
.story-name {
  font-size: 12px;
  color: #262626;
  font-weight: 400;
  margin-top: 4px;
  margin-left: 9px;
}
.story-div {
  display: flex;
}
.small-div {
  margin-left: 19px;
}
</style>