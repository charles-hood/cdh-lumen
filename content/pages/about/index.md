---
title: Our Agents
template: "page"
socialImage: "./elite-gold-black.jpg"
---

<style>
  .agent-container {
    padding: 10px;
    border: 1px solid lightgray;
    margin: 10px;
    overflow: hidden;
    box-sizing: border-box;
  }

  .agent-info {
    float: left;
    padding: 0 10px 0 0;
    border-radius: 30%;
  }

  .agent-image {
    width: 100%;
    max-width: 250px;
    height: auto;
  }

  .agent-bio {
    max-height: 120px; /* Initial max height for the bio */
    overflow: hidden;
    transition: max-height 0.3s ease-out;
  }

  .read-more-link {
    display: block;
    margin-top: 10px;
    text-decoration: underline;
    cursor: pointer;
  }

  .read-more-checkbox {
    display: none;
  }

  .read-more-checkbox:checked + .agent-bio {
    max-height: none; /* Allow the bio to expand when checkbox is checked */
  }

  @media (max-width: 768px) {
    .agent-info {
      float: none;
      margin-bottom: 10px;
    }
  }
</style>

<!-- Agent Sections -->
<!-- Repeat this section for each agent -->

<!-- Agent 1 -->
<div class="agent-container" id="agent1">
  <img src="https://raw.githubusercontent.com/charles-hood/redesign-elite-1/master/content/pages/about/tracylee.jpg" class="agent-info agent-image" />
  <div style="margin-left: 0; overflow: hidden;">
    <span style="display: block;"><strong>Tracy Lee</strong></span>
    <span style="display: block;"><a href="mailto:tracylee.elite@gmail.com">tracylee.elite@gmail.com</a></span>
    <span style="display: block;"><a href="tel:4236532960">(423)653-2960</a></span>
    <div class="agent-bio" id="bio1">
      <p>
        Tracy Lee is an active Realtor and the owner of Elite Realtors LLC. Established in 2020 to bring buying and selling back to putting clients first! Mother of three with degrees in business management, allied sciences, and a background in personal training. Her accomplishments range from Masters Club to Regional multi-million dollar producers club with approximately 40-60 transactions per year.
        She specializes in relocation families, first-time home buyers, and new construction homes. Her priority is quality, and she handles every transaction from start to close.
      </p>
    </div>
    <a href="#bio1" class="read-more-link">Read More</a>
  </div>
</div>

<!-- Agent 2 -->
<div class="agent-container" id="agent2">
  <img src="https://raw.githubusercontent.com/charles-hood/redesign-elite-1/master/content/pages/about/bonniehood.jpg" class="agent-info agent-image" />
  <div style="margin-left: 0; overflow: hidden;">
    <span style="display: block;"><strong>Bonnie Hood</strong></span>
    <span style="display: block;"><a href="mailto:bonniehood.elite@gmail.com">bonniehood.elite@gmail.com</a></span>
    <span style="display: block;"><a href="tel:4234213946">(423) 421-3946</a></span>
    <div class="agent-bio" id="bio2">
      <p>
        Bonnie is a native of North Georgia. She received her REALTOR license in 1997. After gaining valuable experience in real estate, she acquired her Broker’s license. She specializes in residential real estate in the Chattanooga, Tennessee and North Georgia Areas. Whether you are buying or selling your home, it can be a stressful task. So, as your REALTOR, her job is to take the stress out of your hand. Communication is a vital factor to success in Real Estate. That’s why she communicates every step of the way. That gives you assurance knowing that she’s there to guide you. Her goal is to satisfy your needs, whether it is your first home or your last home. She will always put herself in your shoes.
        Bonnie currently resides with husband Stan in Ringgold, Georgia. In her spare time, she enjoys spending time with family and friends, reading, and antique shopping.
      </p>
    </div>
    <a href="#bio2" class="read-more-link">Read More</a>
  </div>
</div>

<!-- Agent 3 -->
<div class="agent-container" id="agent3">
  <img src="https://raw.githubusercontent.com/charles-hood/redesign-elite-1/master/content/pages/about/stanhood.jpg" class="agent-info agent-image" />
  <div style="margin-left: 0; overflow: hidden;">
    <span style="display: block;"><strong>Stan Hood</strong></span>
    <span style="display: block;"><a href="mailto:stanhood.elite@gmail.com">stanhood.elite@gmail.com</a></span>
    <span style="display: block;"><a href="tel:4234439278">(423) 443-9278</a></span>
    <div class="agent-bio" id="bio3">
      <p>
        Stan received his license in 2006 but took a break from real estate in 2010. He returned to real estate in 2019 to work with his wife as a team.
        He specializes in residential properties for buyers and sellers. He will work hard for you from finding your property to the close. Call him today!
      </p>
    </div>
    <a href="#bio3" class="read-more-link">Read More</a>
  </div>
</div>

<!-- Return to Home Button -->
<div style="text-align: center; margin-top: 20px;">
  <a href="https://eliterealtorsllc.com/" style="text-decoration: none; display: inline-block; padding: 10px 20px; background-color: #007BFF; color: #fff; border-radius: 5px; font-weight: bold;">
    Return to Home
  </a>
</div>
