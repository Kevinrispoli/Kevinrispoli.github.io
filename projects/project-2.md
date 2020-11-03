---
layout: project
type: project
image: images/vacay-square.png
title: Survey Form
permalink: projects/vacay
# All dates must be YYYY-MM-DD format!
date: 2015-12-15
labels:
  - Html5
  - Css
  - Jekyl
  - Markdown
summary:__A responsive web application for taking a survey!__
---
[Preview Rendered Code Project 1 at this Location](https://htmlpreview.github.io/?https://github.com/Kevinrispoli/Kevinrispoli.github.io/blob/master/images/index2.html.html),
{% highlight html %}
<div class="container">
  <header class="header">
		<link rel="stylesheet" type="text/css" href="style1.css">
    <h1 id="title" class="text-center">Mushroom Selection For Cooking</h1>
    <p id="description" class="description text-center">
      Thank you for taking the time to fill out this Survey!
    </p>
  </header>
  <form id="survey-form">
    <div class="form-group">
      <label id="name-label" for="name">Name</label>
      <input
			type="name"
        name="name"
        id="name"
        class="form-control"
        placeholder="Enter your Name"
        required
      />
    </div>
		    <div class="form-group">
      <label id="email-label" for="email">Email</label>
      <input
        type="email" 
        name="email"
        id="email"
        class="form-control"
        placeholder="Enter your Email"
        required
      />
    </div>
    <div class="form-group">
			      <p>Would you recommend Mushrooms to cook with?</p>
      <label>
        <input
          name="user-recommend"
          value="definitely"
          type="radio"
          class="input-radio"
          checked
        />Definitely</label
      >
      <label>
				<input
          name="user-recommend"
          value="maybe"
          type="radio"
          class="input-radio"
        />Maybe</label
      >
			<label
        ><input
          name="user-recommend"
          value="not-sure"
          type="radio"
          class="input-radio"
        />Not sure</label
      >
    </div>
		    <div class="form-group">
      <p>
        What is your favorite mushroom to cook with?
      </p>
      <select id="most-like" name="mostLike" class="form-control" required>
        <option disabled selected value>Select an option</option>
        <option value="challenges">Shitake</option>
        <option value="projects">Portabello</option>
        <option value="community">Oyster</option>
        <option value="openSource">Reishi</option>
				      </select>
    </div>

    <div class="form-group">
      <p>
        How would you cook with them?
        <span class="clue">(Check all that apply)</span>
				</p>

      <label
        ><input
          name="prefer"
          value="Chopped"
          type="checkbox"
          class="input-checkbox"
					        />Chopped</label
      >
      <label>
        <input
          name="prefer"
          value="Diced"
          type="checkbox"
          class="input-checkbox"
					/>Diced</label
					>
      <label
        ><input
          name="prefer"
          value="Whole"
          type="checkbox"
          class="input-checkbox"
        />Whole</label
      >
      <label
        ><input
          name="prefer"
          value="Seasoned"
					type="checkbox"    
					class="input-checkbox"
					/>Seasoned</label>
      <label
        ><input
          name="prefer"
          value="spicy"
          type="checkbox"
          class="input-checkbox"
        />spicy</label
      >
      <label
        ><input
				name="prefer"
				value="A small amount"
          type="checkbox"
          class="input-checkbox"
        />A small amount</label
      >
      <label
        ><input
          name="prefer"
          value="more than one dish"
					type="checkbox"
          class="input-checkbox"
        />More than one dish</label
      >
      <label
        ><input
          name="prefer"
          value="Vitamin Rich"
          type="checkbox"
          class="input-checkbox"
        />Vitamin Rich</label
      >
      
			<label
        ><input
          name="prefer"
          value="Flavorfull"
          type="checkbox"
          class="input-checkbox"
        />Flavorfull</label
				>
				 <label
        ><input
          name="prefer"
          value="Brand Name"
          type="checkbox"
          class="input-checkbox"
        />Brand Name</label
				>
				      <label
        ><input
          name="prefer"
          value="For Dinnerbv cc "
          type="checkbox"
          class="input-checkbox"
        />For Dinner</label
      >
    </div>

    <div class="form-group">
      <p>Any Recipes To Share?</p>
      <textarea
        id="comments"
        class="input-textarea"
        name="comment"
        placeholder="Enter your comment here..."
      ></textarea>
    </div>

    <div class="form-group">
      <button type="submit" id="submit" class="submit-button">
				Submit
      </button>
    </div>
  </form>
</div>
{% endhighlight %}
