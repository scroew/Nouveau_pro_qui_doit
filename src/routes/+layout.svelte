<script>
	import Header from './Header.svelte';
	import './styles.css';
</script>

<div class="app">
	<Header />

	<main>
		<slot />
	</main>

<footer>

      <h5>Des questions ? Appelez le 0474-989-756</h5>
      <div class="colonnes">

      <div class="colonne">
          <p>Relations clients</p>
          <p>Relations Investissseurs</p>
          <p>Modes de lecture</p>
          <p>Mentions légales</p>
      </div>
      <div class="colonne">
          <p>Centre d'aide</p>
          <p>Les meilleurs protecteurs</p>
          <p>Entreprise mondiale</p>
          <p>Chiffre d'affaire</p>
          <p>Les arbres</p>
      </div>

      <div class="colonne">
          <p>FAQ</p>
          <p>Recrutement</p>
          <p>Conditions d'utilisation</p>
          <p>Nous contacter</p>
      
      </div>
      <div class="colonne">

          <p>Compte</p>
          <p>S'enregistrer</p>
          <p>Se connecter</p>
          <p>Nous contacter</p>
      
      </div>
      
      </div>

 				<p>CROENNE Maxime codeur</p>
				 
    </footer>

</div>
