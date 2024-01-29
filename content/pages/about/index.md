---
title: Our Agents
template: "page"
socialImage: "./elite-gold-black.jpg"
---

<style>
  .agent-container {
    position: relative;
    padding: 10px;
    border: 1px solid lightgray;
    margin: 10px;
    overflow: hidden;
    box-sizing: border-box;
  }

  .read-more-link {
    cursor: pointer;
    color: blue;
    text-decoration: underline;
  }

  .agent-bio {
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.3s ease-out;
  }

  .agent-info-container:focus-within .read-more-link {
    display: none;
  }

  .agent-info-container:focus-within .agent-bio {
    max-height: 100%;
  }

  .agent-info-container {
    display: flex;
    align-items: center;
    flex-direction: column;
  }

  .agent-info {
    flex-grow: 1;
    padding: 0 10px;
  }

  .agent-image {
    width: 100%;
    max-width: 250px;
    height: auto;
  }

  @media only screen and (max-width: 600px) {
    .agent-info-container {
      flex-direction: column;
    }

    .agent-info {
      padding: 10px;
    }

    .agent-image {
      max-width: 100%;
    }
  }
</style>

<!-- Agent 1 -->
<div class="agent-container">
  <div class="agent-info-container" tabindex="0">
    <img src="https://raw.githubusercontent.com/charles-hood/redesign-elite-1/master/content/pages/about/tracylee.jpg" class="agent-info agent-image" />
    <div class="agent-info">
      <span style="display: block;"><strong>Tracy Lee</strong></span>
      <span style="display: block;"><a href="mailto:tracylee.elite@gmail.com">tracylee.elite@gmail.com</a></span>
      <span style="display: block;"><a href="tel:4236532960">(423)653-2960</a></span>
    </div>
    <label class="read-more-link">Read More</label>
    <div class="agent-bio">
      <p>
        Tracy Lee is an active Realtor and the owner of Elite Realtors LLC. Established in 2020 to bring buying and selling back to putting clients first! Mother of three with degrees in business management, allied sciences, and a background in personal training. Her accomplishments range from Masters Club to Regional multi-million dollar producers club with approximately 40-60 transactions per year.
        She specializes in relocation families, first-time home buyers, and new construction homes. Her priority is quality, and she handles every transaction from start to close.
      </p>
    </div>
  </div>
</div>

<!-- Repeat for other agents -->

<!-- Return to Home Button -->
<div style="text-align: center; margin-top: 20px;">
  <a href="https://eliterealtorsllc.com/" style="text-decoration: none; display: inline-block; padding: 10px 20px; background-color: #007BFF; color: #fff; border-radius: 5px; font-weight: bold;">
    Return to Home
  </a>
</div>
