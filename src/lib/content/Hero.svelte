<script>
  import FlightSearchForm from "$lib/content/FlightSearchForm.svelte";

  let clientID = "IZ9ClO4-rCO5iTEQY9VFTc2L1RBl-3F5D2TdBiOBLLA";
  let endpoint = `https://api.unsplash.com/photos/random/?landscape&collections=Y4PpIW6NUlc&client_id=${clientID}`;
  let imageLocation = "Secret Location";
  let jsonData = {
    id: "AlBgcDfDG_s",
    created_at: "2018-06-27T05:09:52-04:00",
    updated_at: "2022-05-28T10:04:25-04:00",
    promoted_at: null,
    width: 5834,
    height: 3895,
    color: "#f3f3f3",
    blur_hash: "L;I~0;%LWUkC_4xZoMj]bcn$WCWB",
    description:
      "Life isn’t all about the grades you get, sometimes it’s about the hands you shake. This photo was take on June 24th, 2018 I met a guy online who thought about the location when we arrived I realized this was one of the most iconic views Texas had to offer. A burgeoning town, with a rich and vibrant culture, home to southern hospitality. So here’s your ticket to a time now past. Live. Love. Laugh. And don’t forget to enjoy the art we eternally create.",
    alt_description: "photo of city",
    urls: {
      raw: "https://images.unsplash.com/photo-1530089711124-9ca31fb9e863?ixid=MnwzMzI5NzV8MHwxfHJhbmRvbXx8fHx8fHx8fDE2NTM3ODQwNjk&ixlib=rb-1.2.1",
      full: "https://images.unsplash.com/photo-1530089711124-9ca31fb9e863?crop=entropy&cs=tinysrgb&fm=jpg&ixid=MnwzMzI5NzV8MHwxfHJhbmRvbXx8fHx8fHx8fDE2NTM3ODQwNjk&ixlib=rb-1.2.1&q=80",
      regular:
        "https://images.unsplash.com/photo-1530089711124-9ca31fb9e863?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzMzI5NzV8MHwxfHJhbmRvbXx8fHx8fHx8fDE2NTM3ODQwNjk&ixlib=rb-1.2.1&q=80&w=1080",
      small:
        "https://images.unsplash.com/photo-1530089711124-9ca31fb9e863?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzMzI5NzV8MHwxfHJhbmRvbXx8fHx8fHx8fDE2NTM3ODQwNjk&ixlib=rb-1.2.1&q=80&w=400",
      thumb:
        "https://images.unsplash.com/photo-1530089711124-9ca31fb9e863?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzMzI5NzV8MHwxfHJhbmRvbXx8fHx8fHx8fDE2NTM3ODQwNjk&ixlib=rb-1.2.1&q=80&w=200",
      small_s3: "https://s3.us-west-2.amazonaws.com/images.unsplash.com/small/photo-1530089711124-9ca31fb9e863",
    },
    links: {
      self: "https://api.unsplash.com/photos/AlBgcDfDG_s",
      html: "https://unsplash.com/photos/AlBgcDfDG_s",
      download: "https://unsplash.com/photos/AlBgcDfDG_s/download?ixid=MnwzMzI5NzV8MHwxfHJhbmRvbXx8fHx8fHx8fDE2NTM3ODQwNjk",
      download_location: "https://api.unsplash.com/photos/AlBgcDfDG_s/download?ixid=MnwzMzI5NzV8MHwxfHJhbmRvbXx8fHx8fHx8fDE2NTM3ODQwNjk",
    },
    categories: [],
    likes: 614,
    liked_by_user: false,
    current_user_collections: [],
    sponsorship: null,
    topic_submissions: {},
    user: {
      id: "uqWG0xQUAyw",
      updated_at: "2022-05-26T13:55:44-04:00",
      username: "csfoto",
      name: "Carlos Alfonso",
      first_name: "Carlos",
      last_name: "Alfonso",
      twitter_username: null,
      portfolio_url: null,
      bio: "Take a deep breath and share a smile (:",
      location: "Austin, Texas",
      links: {
        self: "https://api.unsplash.com/users/csfoto",
        html: "https://unsplash.com/@csfoto",
        photos: "https://api.unsplash.com/users/csfoto/photos",
        likes: "https://api.unsplash.com/users/csfoto/likes",
        portfolio: "https://api.unsplash.com/users/csfoto/portfolio",
        following: "https://api.unsplash.com/users/csfoto/following",
        followers: "https://api.unsplash.com/users/csfoto/followers",
      },
      profile_image: {
        small: "https://images.unsplash.com/profile-1530091143751-9fac3b1ca6c2?ixlib=rb-1.2.1&crop=faces&fit=crop&w=32&h=32",
        medium: "https://images.unsplash.com/profile-1530091143751-9fac3b1ca6c2?ixlib=rb-1.2.1&crop=faces&fit=crop&w=64&h=64",
        large: "https://images.unsplash.com/profile-1530091143751-9fac3b1ca6c2?ixlib=rb-1.2.1&crop=faces&fit=crop&w=128&h=128",
      },
      instagram_username: null,
      total_collections: 0,
      total_likes: 29,
      total_photos: 2,
      accepted_tos: false,
      for_hire: false,
      social: { instagram_username: null, portfolio_url: null, twitter_username: null, paypal_email: null },
    },
    exif: { make: "NIKON CORPORATION", model: "NIKON D610", name: "NIKON CORPORATION, NIKON D610", exposure_time: "0.4", aperture: "2.8", focal_length: "21.0", iso: 80 },
    location: { title: null, name: null, city: null, country: null, position: { latitude: null, longitude: null } },
    views: 3698976,
    downloads: 34546,
  };
  let imgBgMd = `url(${jsonData.urls.full}&w=2400) center center/cover no-repeat`;
  let imgAriaLabel = `${jsonData.alt_description}`;

  getUnsplashImage();
  


  function populateImage(json) {
    imgBgMd = `url(${json.urls.full}&w=2400) center center/cover no-repeat`;
    imgAriaLabel = `${json.alt_description}`;
    if (json.location.title) {
      imageLocation = `${json.location.title}`;
    } else if (json.id === "AlBgcDfDG_s") {
      imageLocation = `Austin, TX`;
    } else if (json.description) {
      imageLocation = `${json.description}`;
    }
  }
  function getUnsplashImage() {
    fetch(endpoint)
      .then(function (response) {
        return response.json();
      })
      .then(function (jsonData) {
        // Put the object into storage
        //localStorage.setItem('cachedJsonData', JSON.stringify(jsonData));
        populateImage(jsonData);
      })
      .catch(function (error) {
        console.log(`Error: ${error}`);
      });
  }
  // document.addEventListener("DOMContentLoaded", function (event) {
  //     //document.querySelector("html").classList.add("loaded");
  // });
</script>

<div class="fallback-hero">
  <auro-background id="hero" role="img" inset="md" insetMd="xl" bgMd={imgBgMd}>
    <div class="container">
      <div class="img-container">
        <FlightSearchForm />
      </div>
      <span id="location">{imageLocation}</span>
    </div>
  </auro-background>
</div>

<style>
  span#location {
    display: none;
  }

  @media screen and (min-width: 1024px) {
    span#location {
      display: inline;
      float: right;
      color: white;
      text-shadow: 1px 1px 5px black;
    }
    .fallback-hero {
      background-color: var(--auro-color-background-lighter);
    }
  }
  @media screen and (min-width: 1024px) {
    .img-container {
      margin: 5vw auto;
    }
  }
  @media screen and (min-width: 2048px) {
    .img-container {
      margin: 6vw auto;
    }
  }

  .container {
    display: block;
    max-width: 1232px;
    margin: auto;
    padding: var(--padding);
  }
</style>
