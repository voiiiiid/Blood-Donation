<script>

  import { Link, link } from "svelte-routing";

</script>
<!-- the main heading -->
<div class="hero min-h-screen" style="background-image: url(https://daisyui.com/images/stock/photo-1507358522600-9f71e620c44e.jpg);">
  <div class="hero-overlay bg-opacity-60"></div>
  <div class="hero-content text-center text-neutral-content">
    <div class="max-w-md">
      <h1 class="mb-5 text-5xl font-bold">Hey LifeSaver!! Ready to Donate Blood?</h1>
      <p class="mb-5">We need your donation to save local lives! Click the button below to find a location to donate blood.</p>
      <button class="btn btn-primary">Make an Appointment.</button>
    </div>
  </div>
</div>

<div class="hero min-h-screen bg-base-200">
  <div class="hero-content flex-col lg:flex-row-reverse">
    <img src="blood1.jpeg" class="max-w-sm rounded-lg shadow-2xl" />
    <div>
      <h1 class="text-5xl font-bold">HOSPITALS,
        Partner With Us</h1>
      <p class="py-6">Giving back to the community is in our blood. We know it’s the same for community hospitals too. Saving more lives means providing for more hospitals. We’d love to support the place in your community where saving lives happens.</p>
      <button class="btn btn-primary">Locate centers</button>
    </div>
  </div>
</div>

<div class="hero min-h-screen bg-base-200">
  <div class="hero-content text-center">
    <div class="max-w-md">
      <h1 class="text-5xl font-bold">Donor Eligibility Changes!</h1>
      <p class="py-6">You may not be able to donate blood immediately – please read details below to determine your eligibility. </p>
      <button class="btn btn-primary">Learn More</button>
    </div>
  </div>
</div>

<div class="carousel w-full">
  <div id="slide1" class="carousel-item relative w-full">
    <img src="blood1.jpeg" class="w-full" />
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide4" class="btn btn-circle">❮</a> 
      <a href="#slide2" class="btn btn-circle">❯</a>
      <button class="btn btn-primary">Learn More</button>
    </div>
  </div> 
  <div id="slide2" class="carousel-item relative w-full">
    <img src="/images/stock/photo-1609621838510-5ad474b7d25d.jpg" class="w-full" />
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide1" class="btn btn-circle">❮</a> 
      <a href="#slide3" class="btn btn-circle">❯</a>
    </div>
  </div> 
  <div id="slide3" class="carousel-item relative w-full">
    <img src="/images/stock/photo-1414694762283-acccc27bca85.jpg" class="w-full" />
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide2" class="btn btn-circle">❮</a> 
      <a href="#slide4" class="btn btn-circle">❯</a>
    </div>
  </div> 
  <div id="slide4" class="carousel-item relative w-full">
    <img src="/images/stock/photo-1665553365602-b2fb8e5d1707.jpg" class="w-full" />
    <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
      <a href="#slide3" class="btn btn-circle">❮</a> 
      <a href="#slide1" class="btn btn-circle">❯</a>
    </div>
  </div>
</div>

<table>
  <td>
    <div class="card w-96 bg-base-100 shadow-xl">
      <figure><img src="blood1.jpeg" alt="Shoes" /></figure>
      <div class="card-body">
        <h2 class="card-title">Shoes!</h2>
        <p>Need help with your donor portal, making an appointment, or something else? Our Donor Response Center is ready to help!</p>
        <div class="card-actions justify-end">
          <button class="btn btn-primary">Contact Us</button>
        </div>
      </div>
    </div>
  </td>
  <td>
    <div class="card w-96 bg-base-100 shadow-xl">
      <figure><img src="blood1.jpeg" alt="Shoes" /></figure>
      <div class="card-body">
        <h2 class="card-title">Shoes!</h2>
        <p>We’re not far away. Find the nearest blood donation center or blood drive near you.</p>
        <div class="card-actions justify-end">
          <button class="btn btn-primary">Find a Location</button>
        </div>
      </div>
    </div>
  </td>
  <td>
    <div class="card w-96 bg-base-100 shadow-xl">
      <figure><img src="blood1.jpeg" alt="Shoes" /></figure>
      <div class="card-body">
        <h2 class="card-title">Shoes!</h2>
        <p>Have questions about donating or blood donation requirements? We’re the experts, and we’re all ears.</p>
        <div class="card-actions justify-end">
          <button class="btn btn-primary">View the Process</button>
        </div>
      </div>
    </div>
  </td>
</table>
