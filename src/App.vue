
<template>


  <div class="cards">

    <div class="cardOne">

      <div class="avatarDetails">

     
          <img :src="info.avatar_url" alt="profile pics" class="avatar" />
    
        <div class="avatarName">
          <h1>{{ info.name }}</h1>
          <p>{{ info.login }}</p>
        </div>
      </div>

      <p>{{ info.bio }}</p>

      <button class="edit">Edit profile</button>

      <div class="follows">
        

        <span>
          <a href="https://github.com/amycruz97?tab=followers">
            <svg
              text="gray-light"
              height="16"
              class="octicon octicon-people text-gray-light"
              viewBox="0 0 16 16"
              version="1.1"
              width="16"
              aria-hidden="true" >
              <path
                fill-rule="evenodd"
                d="M5.5 3.5a2 2 0 100 4 2 2 0 000-4zM2 5.5a3.5 3.5 0 115.898 2.549 5.507 5.507 0 013.034 4.084.75.75 0 11-1.482.235 4.001 4.001 0 00-7.9 0 .75.75 0 01-1.482-.236A5.507 5.507 0 013.102 8.05 3.49 3.49 0 012 5.5zM11 4a.75.75 0 100 1.5 1.5 1.5 0 01.666 2.844.75.75 0 00-.416.672v.352a.75.75 0 00.574.73c1.2.289 2.162 1.2 2.522 2.372a.75.75 0 101.434-.44 5.01 5.01 0 00-2.56-3.012A3 3 0 0011 4z"></path>
            </svg>
            <span class="follow"> {{ info.followers }} </span>
            followers .
          </a>
        </span>

        <span>
          <a href="https://github.com/amycruz97?tab=following">
            <span class="follow"> {{ info.following }}  </span>
            following .
          </a>
        </span>

        <span>
          <a href="https://github.com/amycruz97?tab=stars">
            <svg
              text="gray-light"
              height="16"
              class="octicon octicon-star text-gray-light"
              viewBox="0 0 16 16"
              version="1.1"
              width="16"
              aria-hidden="true"
            >
              <path
                fill-rule="evenodd"
                d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"
              ></path>
            </svg>
            <span class="follow">64</span>
          </a>
        </span>
      </div>

       <div class="location">
                    <svg class="octicon octicon-location" viewBox="0 0 16 16" version="1.1" width="16" height="16"
                        aria-hidden="true">
                        <path fill-rule="evenodd"
                            d="M11.536 3.464a5 5 0 010 7.072L8 14.07l-3.536-3.535a5 5 0 117.072-7.072v.001zm1.06 8.132a6.5 6.5 0 10-9.192 0l3.535 3.536a1.5 1.5 0 002.122 0l3.535-3.536zM8 9a2 2 0 100-4 2 2 0 000 4z">
                        </path>
                    </svg>
                    <span>{{ info.location }}</span>
                </div>

                <div class="userName">
                    <i class="fab fa-twitter"></i>
                    <span><a href="https://twitter.com/AmarachiAmaechi"
                            class="twitter">@{{ info.twitter_username }}</a></span>

                </div>


                <hr class="hideHr">

                <div class="highlights">

                    <h2>Highlights</h2>
                    <svg class="octicon octicon-north-star text-gray-light mr-1" viewBox="0 0 16 16" version="1.1"
                        width="16" height="16" aria-hidden="true">
                        <path
                            d="M8.5.75a.75.75 0 00-1.5 0v5.19L4.391 3.33a.75.75 0 10-1.06 1.061L5.939 7H.75a.75.75 0 000 1.5h5.19l-2.61 2.609a.75.75 0 101.061 1.06L7 9.561v5.189a.75.75 0 001.5 0V9.56l2.609 2.61a.75.75 0 101.06-1.061L9.561 8.5h5.189a.75.75 0 000-1.5H9.56l2.61-2.609a.75.75 0 00-1.061-1.06L8.5 5.939V.75z">
                        </path>
                    </svg>
                    <span>Arctic Code Vault Contributor</span>

                </div>
                <hr>


                <div class="organisation">
                    <h2>Organisation</h2>
                    <img src="https://avatars2.githubusercontent.com/u/8825476?s=60&v=4" alt="organisation">
                </div>

   

      



      

    </div>

    <div class="cardTwo">
     
       <div class="header">

                    <div class="headerContent">
                        <span class="headerIcon">
                            <a href="https://github.com/amycruz97" >
                                <svg class="headerIcons octicon octicon-book UnderlineNav-octicon hide-sm" height="16"
                                    viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true">
                                    <path fill-rule="evenodd"
                                        d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z">
                                    </path>
                                </svg>
                                <span>Overview</span>
                            </a>
                        </span>

                        <span class="headerIcon">
                            <svg class="headerIcons octicon octicon-repo UnderlineNav-octicon hide-sm" height="16"
                                viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true">
                                <path fill-rule="evenodd"
                                    d="M2 2.5A2.5 2.5 0 014.5 0h8.75a.75.75 0 01.75.75v12.5a.75.75 0 01-.75.75h-2.5a.75.75 0 110-1.5h1.75v-2h-8a1 1 0 00-.714 1.7.75.75 0 01-1.072 1.05A2.495 2.495 0 012 11.5v-9zm10.5-1V9h-8c-.356 0-.694.074-1 .208V2.5a1 1 0 011-1h8zM5 12.25v3.25a.25.25 0 00.4.2l1.45-1.087a.25.25 0 01.3 0L8.6 15.7a.25.25 0 00.4-.2v-3.25a.25.25 0 00-.25-.25h-3.5a.25.25 0 00-.25.25z">
                                </path>
                            </svg>
                            <a href="https://github.com/amycruz97?tab=repositories">
                                <span class="">Respositories
                                    <span class="repoNum"> {{repo.length}} </span>
                                </span>
                            </a>
                        </span>

                        <span class="headerIcon">
                            <a href="https://github.com/amycruz97?tab=projects">
                                <svg class="headerIcons octicon octicon-project UnderlineNav-octicon hide-sm"
                                    height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true">
                                    <path fill-rule="evenodd"
                                        d="M1.75 0A1.75 1.75 0 000 1.75v12.5C0 15.216.784 16 1.75 16h12.5A1.75 1.75 0 0016 14.25V1.75A1.75 1.75 0 0014.25 0H1.75zM1.5 1.75a.25.25 0 01.25-.25h12.5a.25.25 0 01.25.25v12.5a.25.25 0 01-.25.25H1.75a.25.25 0 01-.25-.25V1.75zM11.75 3a.75.75 0 00-.75.75v7.5a.75.75 0 001.5 0v-7.5a.75.75 0 00-.75-.75zm-8.25.75a.75.75 0 011.5 0v5.5a.75.75 0 01-1.5 0v-5.5zM8 3a.75.75 0 00-.75.75v3.5a.75.75 0 001.5 0v-3.5A.75.75 0 008 3z">
                                    </path>
                                </svg>
                                <span>Projects</span>
                            </a>
                        </span>

                        <span class="headerIcon">
                            <a href="https://github.com/amycruz97?tab=packages">
                                <svg class="headerIcons octicon octicon-package UnderlineNav-octicon hide-sm"
                                    height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true">
                                    <path fill-rule="evenodd"
                                        d="M8.878.392a1.75 1.75 0 00-1.756 0l-5.25 3.045A1.75 1.75 0 001 4.951v6.098c0 .624.332 1.2.872 1.514l5.25 3.045a1.75 1.75 0 001.756 0l5.25-3.045c.54-.313.872-.89.872-1.514V4.951c0-.624-.332-1.2-.872-1.514L8.878.392zM7.875 1.69a.25.25 0 01.25 0l4.63 2.685L8 7.133 3.245 4.375l4.63-2.685zM2.5 5.677v5.372c0 .09.047.171.125.216l4.625 2.683V8.432L2.5 5.677zm6.25 8.271l4.625-2.683a.25.25 0 00.125-.216V5.677L8.75 8.432v5.516z">
                                    </path>
                                </svg>
                                <span>Packages</span>
                            </a>
                        </span>


                    </div>


       </div>

        <hr>

           <div class="find">

                    <div class="findinput">
                        <input class="text findInput" placeholder="Find a repository">
                    </div>

                    <div class="selectInput">
                        <span>
                            <select id="select" name="select">
                                <option value="all">Type: All</option>
                                <option value="all">All</option>
                                <option value="private">Private</option>
                                <option value="public">Public</option>
                                <option value="sources">Sources</option>
                                <option value="forked">Forked</option>
                                <option value="archived">Archived</option>
                                <option value="mirrors">Mirrors</option>
                            </select>
                        </span>

                        <span>
                            <select id="select" name="select">
                                <option value="all">Language: All</option>
                                <option value="javascript">Javascript</option>
                                <option value="css">CSS</option>
                                <option value="html">HTML</option>
                            </select>
                        </span>

                        <button class="new"> <a href="https://github.com/new" class="new">
                                <svg class="octicon octicon-repo" viewBox="0 0 16 16" version="1.1" width="16"
                                    height="16" aria-hidden="true">
                                    <path fill-rule="evenodd"
                                        d="M2 2.5A2.5 2.5 0 014.5 0h8.75a.75.75 0 01.75.75v12.5a.75.75 0 01-.75.75h-2.5a.75.75 0 110-1.5h1.75v-2h-8a1 1 0 00-.714 1.7.75.75 0 01-1.072 1.05A2.495 2.495 0 012 11.5v-9zm10.5-1V9h-8c-.356 0-.694.074-1 .208V2.5a1 1 0 011-1h8zM5 12.25v3.25a.25.25 0 00.4.2l1.45-1.087a.25.25 0 01.3 0L8.6 15.7a.25.25 0 00.4-.2v-3.25a.25.25 0 00-.25-.25h-3.5a.25.25 0 00-.25.25z">
                                    </path>
                                </svg>
                                New
                            </a></button>

                    </div>

          </div>
          <hr>
<!-- 
       <div class="repo" v-for="(item, index) in repo.data" :key="index" >
           <repo :data='item'></repo>
         </div>  -->

         <div  v-for="item in repo" :key="item.id" >
        <repo :data="item"></repo>
         </div>


       



    </div>

  </div>
</template>

<script>
import axios from "axios";
import Repo from "./components/Repo";

export default {

 
name: 'app',
  data() {
    return {
      
      info: {},
      repo: {},
    };
  },
  components:{
    Repo,

  },
  mounted() {
    axios
      .get("https://api.github.com/users/amycruz97")
      .then((response) => {
        (this.info = response.data)
      return axios.get('https://api.github.com/users/amycruz97/repos');
      
      })
      .then((response)=>{
       
        response.data.sort((a, b) =>{
          return new Date(b.created_at) - new Date(a.created_at);
        })
         response.data.forEach(element => {
        element.isStarred = false
    })
    this.repo = response.data
        
       
      })
      .catch((error) => console.log(error, "error"));
  },
};
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
 
}
</style>
