<script>
  import Container from "../components/page/Container.svelte";
  import Calc from "../components/calc/Calc.svelte";
  import Header from "../components/page/Header.svelte";
  import Body from "../components/page/Body.svelte";
  import Link from "../components/page/body/Link.svelte";
  import List from "../components/page/body/List.svelte"
</script>

<Container>
  <Header/>
  <Body>
    <p><b class="font-semibold">Takaran</b> <!-- by <Link to="/#">santuy.co</Link> --> adalah website yang berguna untuk menghitung takaran dalam memasak.</p>
    <p>Contohnya seperti :</p>
    <List>Gelas</List>
    <List>Sendok Makan (sdm)</List>
    <List>Sendok Teh (sdt)</List>
    <List>Gram (g)</List>
    <List>mililiter (ml / cc)</List>
    <hr>
    <div class="my-3">
      <h2 class="font-bold my-10 text-center text-2xl">Ukur takaranmu dibawah :</h2>
    </div>
    <Calc/>
  </Body>
</Container>