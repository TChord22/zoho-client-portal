# Log a Ticket Landing Page

The below is sample code for a standard form landing page. You can make adjustments as you see fit. When you copy and paste your code inside of the HTML widget of Zoho Creator. On the right hand side you should see quick drag and drop functions. The very top you should have access to the forms quick function which you can place in the comment added below the code.

To push this forms specific data, you will need to trigger a workflow upon form submission. You can grab the the sample script from the workflow.md file here.

## Provided Code Snippet:

```html
<%{
	%>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:opsz,wght@9..40,300;9..40,500;9..40,700&display=swap" rel="stylesheet">
<style>
	.zc-pb-tile-container {
		padding: 0px !important;
		border-radius: 0 !important;
	}
	.Layout.elemContainment {
		padding: 0 !important;
		border: none !important;
		border-radius: 0 !important;
	}
	.box {
		border-shadow: none;
	}
	.rowBlocks {
		width: 720px;
		max-width: 100%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		align-content: center;
		justify-content: center;
		align-items: center;
		margin: 0 auto;
		gap:10px;
		padding-bottom:50px;
	}
	.rowBlocks h1 {
		width: 100%;
		font-family: 'DM Sans', sans-serif;
		font-weight:700;
	}
	.block {
		width: 49%;
		max-width: 100%;
		flex: 0 0 49%;
	}
	.block i {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		align-content: center;
		justify-content: flex-start;
		align-items: center;
		gap: 10px;
	}
	#header {
		position: relative;
		height:420px;
		overflow: hidden;
		max-width:100%;
	}
	.welcome-message {
		padding: 50px;
		width: 720px;
		max-width: 100%;
		margin: -70px auto 0;
		background-color: white;
		line-height: 1.7em;
		z-index: 0;
		position: absolute;
		right: 0;
		left: 0;
	}
	.welcome-message p {
		font-family: 'DM Sans', sans-serif;
		font-weight:300;
	}
	h1 {
		font-size: 25px;
		line-height:1.1em;
		font-family: 'DM Sans', sans-serif;
		font-weight:700;
		padding-left:10px;
	}
	.hero-banner img {
		width: 100%;
		height: 250px;
		object-fit: cover;
		object-position: bottom;
	}
	/* form[name="Your_Forms_Name"].label-inplace {
    width: auto !important; */
}
	.welcome-header {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-content: center;
    align-items: center;
    justify-content: space-between;
}
i.fa-regular.fa-life-ring {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-content: center;
    justify-content: flex-start;
    align-items: center;
}
i#home-ico {
    font-size: 18px;
    transform: scale(1);
	transition: ease-in-out 0.2s;
	background-color: transparent;
	border-radius: 50%;
	padding:10px 10px 11px;
}
i#home-ico:hover {
    transform: scale(1.2);
	transition: ease-in-out 0.2s;
	background-color: #ef8216;
	padding:10px 10px 11px;
	color:white;
	}
	</style>
	<section id="header">
	<div class="hero-banner">
		<img src="your_banner_image" width="100%">
	</div>
<div class="welcome-message">
<div class="welcome-header">
	<i class="fa-regular fa-life-ring"><h1>Title
</h1></i>
<a href="your-page-url"><i elname="sectionIcon" class="zc-li-solid ui-1-home-minimal" id="home-ico" title="Home"> </i></a>
</div>
<p>Paragraph</p></div>
	</section>
	<section id="body">
	<div class="rowBlocks">
	<!-- Add your form widget here-->
	</section>
<%

}%>
```
