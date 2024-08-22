<script>
  import Layout from "../layout/Layout.svelte";
  import "./social-icons.scss";

  import Discord from "./assets/Discord.png";
  import X from "./assets/X.png";
  import Instagram from "./assets/Instagram.png";
  import TikTok from "./assets/TikTok.png";
</script>

<div id="background" />

<Layout>
  <div id="content-container">
    <div id="content">
      <img
        src="https://pbs.twimg.com/profile_images/1826459469477199872/SNPdUz3E_400x400.jpg"
        alt="User Avatar"
        class="avatar"
        width="100px"
        height="100px"
      />
      <h2>Astro/Alex</h2>
      <div class="social-icon-wrapper">
        <div class="social-icon-container">
          <a href="https://x.com/_ASTRO_ASTRO" target="_blank">
            <img
              src={X}
              width={18}
              height={20}
              alt="X"
              class="social-icon with-push"
            />
          </a>
          <a
            href="https://discord.com/users/945767727484784642"
            target="_blank"
          >
            <img
              src={Discord}
              width={25}
              height={20}
              alt="Discord"
              class="social-icon with-push"
            />
          </a>
          <a
            href="https://www.instagram.com/aspect_astro_live_"
            target="_blank"
          >
            <img
              src={Instagram}
              height={20}
              alt="Discord"
              class="social-icon with-push"
            />
          </a>
          <a href="https://www.tiktok.com/@_astro_astro" target="_blank">
            <img
              src={TikTok}
              height={20}
              alt="Discord"
              class="social-icon with-push"
            />
          </a>
        </div>
      </div>
    </div>
    <a class="credit" href="https://myferr.foo.ng" target="_blank"
      >created by myferr</a
    >
  </div>
</Layout>
