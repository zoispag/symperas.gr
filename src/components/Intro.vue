<template>
  <div>
    <div class="flex flex-grow justify-center px-24 my-12">
      <div class="my-auto mr-32 w-full sm:w-1/2">
        <h1 class="font-bold text-4xl">Συμπεράς Παύλος & Σια Ε.Ε.</h1>
        <p class="text-xl mb-2">Ασφαλιστικοί & Επενδυτικοί Σύμβουλοι</p>
        <p class="text-lg text-gray-600">Πιστοποιημένος financial planner.</p>
      </div>
      <div class="hidden sm:block sm:w-1/3">
        <img :src="hero_main">
      </div>
    </div>

    <div class="flex flex-grow justify-center px-24 my-16">
      <div class="w-1/2 mr-32">
        <img :src="hero_clubs">
      </div>
      <div class="my-auto w-2/3">
        <h2 class="font-bold text-2xl mb-2">Ασφάλιση</h2>
        <div class="mb-2 py-1 bg-blue-700 w-24 rounded-lg"></div>
        <p class="text-lg">Η προστασία μιας οικογένειας από ασφαλιστικούς κινδύνους είναι μια πολύ σοβαρή, δύσκολη και περίπλοκη υπόθεση. Με σωστή αντιμετώπιση των ξεχωριστών δεδομένων της κάθε περίπτωσης υποψήφιου πελάτη, αλλά και με τη σφαιρική γνώση της αγοράς, μπορούμε να δώσουμε τα καλύτερα αποτελέσματα για ένα σωστό και οικονομικό σχεδιασμό.</p>
      </div>
    </div>

    <div class="flex flex-grow justify-center px-24 my-16">
      <div class="my-auto mr-32 w-2/3">
        <h2 class="font-bold text-2xl mb-2">Επένδυση</h2>
        <div class="mb-2 py-1 bg-blue-700 w-24 rounded-lg"></div>
        <p class="text-lg">Η διαχείρηση των κεφαλαίων είναι πολύ δύσκολο γίνει, εάν δεν έχεις ευρύτατη γνώση της αγοράς, των επιλογών που υπάρχουν ανά πάσα στιγμή διαθέσιμες, αλλά και το προσωπικό επενδυτικό προφίλ του υποψήφιου, ώστε το τελικό αποτέλεσμα να σε δικαιώσει. Εμείς με τη εμπειρία και την εξιδείκευση σε αυτό τον τομέα, μπορούμε να διασφαλίσουμε ανάλογα αποτελέσματα.</p>
      </div>
      <div class="w-1/2">
        <img :src="hero_github">
      </div>
    </div><div class="flex flex-grow justify-center px-24 my-16">
      <div class="w-1/2 mr-32">
        <img :src="hero_clubs">
      </div>
      <div class="my-auto w-2/3">
        <h2 class="font-bold text-2xl mb-2">Financial planning</h2>
        <div class="mb-2 py-1 bg-blue-700 w-24 rounded-lg"></div>
        <p class="text-lg">Το FP δεν είναι κάποιο προϊόν. Είναι υπηρεσία. Είναι η διαδικασία της επίτευξης των στόχων ζωής μέσα από την ορθή διαχείρηση των οικονομικών σας. Από την αγορά σπιτιού, στην αποπληρωμή φόρων, και από τον προγραμματισμό της σύνταξης μέχρι προστασία της οικογένειας, τις σπουδές των παιδιών και τη διαχείρηση των αποταμιεύσεων. Μέσω της συλλογής κατάλληλων πληροφοριών, της καταγραφής των προσωπικών αναγκών και επιθυμιών και την ανάλυση της τρέχουσας κατάστασης της αγοράς μπορουμε να σχεδιάσουμε το κατάλληλο προγραμματισμό για να επιτευχούν τα μελλοντικά σας σχέδια.</p>
      </div>
    </div>

    <div class="flex flex-grow justify-center px-24 mt-16 mb-12">
      <div class="my-auto mr-32 w-2/3">
        <h2 class="font-bold text-2xl mb-2">Καριέρα</h2>
        <div class="mb-2 py-1 bg-blue-700 w-24 rounded-lg"></div>
        <p class="text-lg">Ο χώρος των χρηματοασφαλιστικών υπηρεσιών έχει πολύ μεγάλο ενδιαφέρον και πολλές προοπτικές για το μέλλον. Η ενασχόληση με αυτό το επάγγελμα αποφέρει ικανοποιητικά εισοδήματα, αλλά και ηθική ικανοποίηση για τις υπηρεσίες που μπορεί να προσφέρει ένας σύμβουλος στους πελάτες του και την κοινωνία συνολικά. Αν πραγματικά σας ενδιαφέρει μια τέτοια καριέρα με κίνητρα και προοπτικές, μπορείτε να επικοινωνήσετε μαζί μας για περισσότερες πληροφορίες και για να δημιουργήσουμε μαζί τα όνειρά σας.</p>
      </div>
      <div class="w-1/2">
        <img :src="hero_github">
      </div>
    </div>
  </div>
</template>

<script>
import hero_main from '@/assets/images/hero_main.png'
import hero_github from '@/assets/images/hero_github.png'
import hero_clubs from '@/assets/images/hero_clubs.png'

export default {
  name: 'Intro',
  data: function () {
    return {
      hero_main: hero_main,
      hero_github: hero_github,
      hero_clubs: hero_clubs
    }
  }
}
</script>
