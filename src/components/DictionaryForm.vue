<template>
  <div class="bg-blue-700 py-16 px-6 text-white flex justify-center">
    <div class="w-3/4">
      <div class="mb-8">
        <p><strong>Ασφάλιση κατοικίας.</strong> Σημαντικό θέμα, αλλά ίσως περίπλοκο για κάποιους. Τι είναι η ασφαλιστική αξία; Τι είναι η υπασφάλιση; Τι πρέπει να κάνω για να αποζημιωθώ σωστά σε περίπτωση ζημιάς; Για να έχετε μια πρώτη εικόνα για το τι σημαίνει ακριβώς το καθένα από αυτά, μπορείτε να κατεβάσετε ένα λεξικό όρων <strong>ΔΩΡΕΑΝ</strong>.</p>
      </div>
      <div class="mb-2">
        <p class="text-sm mb-1">Email</p>
        <input
          class="bg-gray-300 text-gray-900 focus:outline-0 focus:shadow-outline rounded-lg py-2 px-4 block w-full appearance-none leading-normal"
          type="email"
          placeholder="jane@example.com"
        >
      </div>
      <div class="mb-4">
        <label class="inline-flex items-center">
          <input type="checkbox" class="form-checkbox text-gray-800" />
          <span class="text-sm ml-2">Συναινώ να χρησιμοποιήσετε το email και το όνομα μου προκειμένου να λαμβάνω προωθητικές καμπάνιες και ενημερώσεις.</span>
        </label>
      </div>
      <div>
        <button
          class="bg-white text-sm hover:bg-gray-500 text-blue-700 font-semibold hover:text-white py-2 px-8 border border-gray-500 hover:border-transparent rounded">
          Λήψη
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'DictionaryForm',
}
</script>
