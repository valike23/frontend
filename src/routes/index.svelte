<script>
  import CopyWright from "../components/Nav/CopyWright.svelte";
import Footer from "../components/Nav/Footer.svelte";
import Header from "../components/Nav/Header.svelte";
import TopLine from "../components/Nav/TopLine.svelte";
import MessageModal from "../components/modals/MessageModal.svelte";
import SearchModal from "../components/modals/SearchModal.svelte";
  import AboutUs from "../components/pages/home/AboutUs.svelte";
  import Blogs from "../components/pages/home/Blogs.svelte";
  import Contact from "../components/pages/home/Contact.svelte";
  import ContactInfo from "../components/pages/home/ContactInfo.svelte";
  import Faq from "../components/pages/home/FAQ.svelte";
  import Map from "../components/pages/home/Map.svelte";
  import Programs from "../components/pages/home/Programs.svelte";
  import Slider from "../components/pages/home/Slider.svelte";
  import Teams from "../components/pages/home/Teams.svelte";
import Preloader from "../components/utils/Preloader.svelte";

</script>

<Preloader></Preloader>
<SearchModal></SearchModal>
<MessageModal></MessageModal>
<div id="canvas">
	<div id="box_wrapper">
		<TopLine></TopLine>
		<div class="header_absolute">
			<Header></Header>
			<Slider></Slider>
		</div>
		<ContactInfo></ContactInfo>
		<AboutUs></AboutUs>
		<Programs></Programs>
		<Teams></Teams>
		<Blogs></Blogs>
		<Faq></Faq>
		<Map></Map>
		<Contact></Contact>
		<ContactInfo></ContactInfo>
		<Footer></Footer>
		<CopyWright></CopyWright>
	</div>
</div>