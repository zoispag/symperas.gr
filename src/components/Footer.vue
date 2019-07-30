<template>
  <div class="flex justify-between items-center py-8 px-48 items-stretch">

    <div class="w-2/5">
      <h4 class="font-bold text-base mb-8">Newsletter</h4>
      <input
        class="bg-gray-300 text-gray-900 focus:outline-0 focus:shadow-outline rounded-lg py-2 px-4 block w-full appearance-none leading-normal"
        type="email" placeholder="το e-mail σας"
      >
      <label class="inline-flex items-center mt-4">
        <input type="checkbox" class="form-checkbox text-gray-800" />
        <span class="text-sm ml-2">Έχω διαβάσει, κατανοώ και αποδέχομαι τους όρους χρήσης του ιστότοπου</span>
      </label>
    </div>

    <div class="w-1/4">
      <h4 class="font-bold text-base mb-8">Σχετικά με εμάς</h4>
      <div class="mb-2 text-sm">
        <p class="mb-1"><a class="text-blue-600" href="#">Βιογραφικό</a></p>
        <p class="mb-1"><a class="text-blue-600" href="#">Φιλοσοφία</a></p>
        <p class="mb-1"><a class="text-blue-600" href="#">Δημοσιέυσεις</a></p>
      </div>
    </div>

    <div class="w-1/4 text-sm">
      <h4 class="font-bold text-base mb-8">Στοιχεία επικοινωνίας</h4>
      <div class="flex mb-2">
        <svg class="w-8 h-8 fill-current mr-4 text-gray-700 my-auto" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 460.3 460.3">
          <path d="M230.1 121L66 256.2l-.2.8-.1.9v137c0 5 1.8 9.3 5.4 12.9 3.6 3.6 8 5.4 12.9 5.4h109.6V303.7h73.1v109.6h109.6c5 0 9.3-1.8 12.9-5.4 3.6-3.6 5.4-8 5.4-12.9V258a4 4 0 0 0-.3-1.7L230.1 120.9z" />
          <path d="M457.1 225.4l-62.5-52V57a8.9 8.9 0 0 0-9.1-9.1h-54.9c-2.6 0-4.8.8-6.5 2.5a8.9 8.9 0 0 0-2.6 6.6v55.7l-69.7-58.3c-6-5-13.3-7.4-21.6-7.4-8.4 0-15.7 2.5-21.7 7.4L3.2 225.4a8.3 8.3 0 0 0-3.2 6.2c-.2 2.5.5 4.8 2 6.7l17.7 21.1a9.7 9.7 0 0 0 6 3.2c2.3.1 4.6-.5 6.9-2L230 95.8l197.6 164.8c1.5 1.3 3.5 2 6 2h.9a9.8 9.8 0 0 0 6-3.2l17.7-21.1c1.5-2 2.2-4.2 2-6.7a8.3 8.3 0 0 0-3.2-6.2z" />
        </svg>
        <div>
          <p class="font-base">Συρράκου 20, 10444</p>
          <p class="font-base">Αθήνα, Αττική, ΕΛΛΑΔΑ</p>
        </div>
      </div>

      <div class="flex mb-4">
        <svg class="w-8 h-8 fill-current mr-4 text-gray-700" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 14 14">
          <path d="M7 9L5.3 7.5l-5 4.2c.2.2.4.3.7.3h12c.3 0 .5-.1.7-.3l-5-4.2L7 9z" />
          <path d="M13.7 2.3A1 1 0 0 0 13 2H1a1 1 0 0 0-.7.3L7 8l6.7-5.7zM0 2.9v8.3l4.8-4.1zM9.2 7.1l4.8 4.1V2.9z" />
        </svg>
        <div>
          <p class="font-base mt-1"><a class="text-blue-600" href="mailto:symperasp@gmail.com">symperasp@gmail.com</a></p>
        </div>
      </div>

      <div class="flex mb-4">
        <svg class="w-8 h-8 fill-current mr-4 text-gray-700" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 51.4 51.4">
          <path d="M26 12.3c8.7 0 14-.5 14.8 9.1h10.6c0-14.9-13-16.9-25.7-16.9S.1 6.5.1 21.5h10.4c.8-9.9 6.9-9.3 15.5-9.2zM5.3 26.2c2.6 0 4.7.2 5.2-2.4v-1.2H0c0 3.8 2.4 3.6 5.3 3.6zM40.9 22.6h-.1v1.2c.6 2.4 2.7 2.2 5.3 2.2 3 0 5.3.2 5.3-3.4H41z" />
          <path d="M35.7 20v-1.4c0-.7-.8-.7-1.7-.7h-1.6c-1 0-1.7 0-1.7.7v2.3h-11v-2.3c0-.7-.8-.7-1.7-.7h-1.6c-1 0-1.7 0-1.7.7v2.8a110.9 110.9 0 0 0-11 15v9c0 .8.7 1.5 1.5 1.5h40c.8 0 1.5-.7 1.5-1.5v-9c-.3-1.3-8.5-12.4-11-15V20zM19.2 37.7a1.5 1.5 0 1 1 0-2.9 1.5 1.5 0 0 1 0 3zm0-5a1.5 1.5 0 1 1 0-2.9 1.5 1.5 0 0 1 0 3zm0-5a1.5 1.5 0 1 1 0-2.9 1.5 1.5 0 0 1 0 3zm6 10a1.5 1.5 0 1 1 0-2.9 1.5 1.5 0 0 1 0 3zm0-5a1.5 1.5 0 1 1 0-2.9 1.5 1.5 0 0 1 0 3zm0-5a1.5 1.5 0 1 1 0-2.9 1.5 1.5 0 0 1 0 3zm6 10a1.5 1.5 0 1 1 0-2.9 1.5 1.5 0 0 1 0 3zm0-5a1.5 1.5 0 1 1 0-2.9 1.5 1.5 0 0 1 0 3zm0-5a1.5 1.5 0 1 1 0-2.9 1.5 1.5 0 0 1 0 3z" />
        </svg>
        <div>
          <p class="font-base mt-1"><a class="text-gray-900" href="tel:+302114056989">+30 211 40 56 989</a></p>
        </div>
      </div>

      <div class="flex mb-4">
        <svg class="w-8 h-8 fill-current mr-4 text-gray-700" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 27.4 27.4">
          <path d="M19.5 0H7.9a2 2 0 0 0-2 2v23.4c0 1.1 1 2 2 2h11.6a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2zm-8.6 1.2h5.7c.1 0 .2.2.2.5s0 .5-.2.5h-5.7c-.2 0-.3-.2-.3-.5s.1-.5.3-.5zm2.8 24.3a1.3 1.3 0 1 1 0-2.6 1.3 1.3 0 0 1 0 2.6zM20 21H7.4V3.4H20V21z" />
        </svg>
        <div>
          <p class="font-base mt-1"><a class="text-gray-900" href="tel:+306944548474">+30 6944 54 84 74</a></p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer',
}
</script>
