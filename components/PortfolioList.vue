<template>
    <div>
      <div class="serviceList pb-5">
        <div class="container">
          <div class="row row-cols-1 g-5 row-cols-sm-2 row-cols-md-3 g-3">
            <div class="col" v-for="item in serviceList" :key="item.id">
              <div class="card shadow-sm">
                  <img 
                  :src="item.image" 
                  :alt="item.title"
                  />
                <div class="card-body">
                  <h3>{{item.title}}</h3>
                  <p class="card-text">
                    This is a wider card with supporting text below as a natural
                    lead-in to additional content. This content is a little bit
                    longer.
                  </p>
                  <div
                    class="d-flex justify-content-between align-items-center"
                  ></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        serviceList: [
          {
            id: "1",
            title: "Portfolio 1",
            image: "/img/placeholder/640x480.jpg",
          },
          {
            id: "23",
            title: "Portfolio 2",          
            image: "/img/placeholder/640x480.jpg",
          },
          {
            id: "34",
            title: "Portfolio 3",          
            image: "/img/placeholder/640x480.jpg",
          },
          {
            id: "45",
            title: "Portfolio 4",          
            image: "/img/placeholder/640x480.jpg",
          },
          {
            id: "56",
            title: "Portfolio 5",          
            image: "/img/placeholder/640x480.jpg",
          },
          {
            id: "67",
            title: "Portfolio 6",          
            image: "/img/placeholder/640x480.jpg",
          },
        ],
      };
    },
  };
  </script>
  
  <script setup>
  const option = {
    headers: {
      SameSite: "Strict"
    }
  }
  </script>