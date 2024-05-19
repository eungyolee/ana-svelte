<script>
  const hashtags = [
    "Front-End",
    "Student",
    "Developer",
    "Korean",
    "AnA"
  ];
</script>

<div class="main">
  <div class="profile-card">
    <div class="profile-image"></div>
    <h1 class="name">
      Eun-Gyo Lee<br />
      이은교
    </h1>
  </div>
  <div class="my-info">
    <h2 class="school">
      Sunrin Internet High School<br />
      119th Division of Software<br />
      <span class="light">
        선린인터넷고등학교<br />
        119기 소프트웨어과
      </span>
    </h2>
    <h3 class="hashtags">
      { #each hashtags as value }
        <div class="hashtag">{value}</div> 
      { /each }
    </h3>
  </div>
</div>

<style>
   @import url("https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable.min.css");

  * {
    font-family: 'Pretendard Variable', sans-serif;
    font-weight: 600;
  }

  .light {
    font-weight: 400;
  }

  .main {
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 70%;
    height: 100vh;
    flex-direction: row;
    text-align: center;
  }

  .profile-card {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  .profile-image {
    width: 400px;
    height: 400px;
    border-radius: 50%;
    background-image: url('https://avatars.githubusercontent.com/u/85398698?v=4');
    background-size: cover;
    background-position: center;
  }

  .name {
    font-size: 2rem;
  }

  .school {
    font-size: 1.8rem;
  }

  .hashtags {
    font-size: 1.5rem;
    width: 450px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
    flex-wrap: wrap;
  }

  .hashtag {
    margin: 7px;
    padding: 15px;
    border-radius: 30px;
    background-color: #333333;
  }
</style>