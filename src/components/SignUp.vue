<template>
    <div class="flex min-h-full items-center justify-center py-12 px-4 sm:px-6 lg:px-8">
  <div class="w-full max-w-xl space-y-8 md:bg-slate-50 md:bg-opacity-50 md:p-10 md:rounded-[3.5rem]"> 
    <div>
      <img class="mx-auto h-12 w-auto" src="https://getwaya.com/wp-content/uploads/2022/10/Waya-Alt-1.png" alt="Your Company">
      <h2 class="mt-6 text-center text-3xl font-bold tracking-tight text-gray-900">Sign Up</h2>

    </div>
    <form class="mt-8 space-y-6" action="#" method="POST">
      <input type="hidden" name="remember" value="true">
      <div class="-space-y-px rounded-md shadow-sm">
        <!--First Name-->
        <div>
          <label for="first-name" class="sr-only">First name</label>
          <input id="first-name" name="first-name" type="text" autocomplete="first name" required class="mb-1.5 relative block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 text-gray-900 placeholder-gray-500 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-2 focus:ring-slate-500 sm:text-sm" placeholder="First name">
        </div>
        <!--Middle Name-->
        <div>
          <label for="middle-name" class="sr-only">Middle name</label>
          <input id="middle-name" name="middle-name" type="text" autocomplete="middle name" required class="mb-1.5 relative block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 text-gray-900 placeholder-gray-500 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-2 focus:ring-slate-500 sm:text-sm" placeholder="Middle name">
        </div>
        <!--Last Name-->
        <div>
          <label for="last-name" class="sr-only">Last name</label>
          <input id="last-name" name="last-name" type="text" autocomplete="last name" required class="mb-1.5 relative block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 text-gray-900 placeholder-gray-500 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-2 focus:ring-slate-500 sm:text-sm" placeholder="Last name">
        </div>
        <!--Email-->
        <div>
          <label for="email-address" class="sr-only">Email address</label>
          <input id="email-address" name="email" type="email" autocomplete="email" required class="mb-1.5 relative block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 text-gray-900 placeholder-gray-500 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-2 focus:ring-slate-500 sm:text-sm" placeholder="Email address">
        </div>
        <!--Mobile-->
        <div>
          <label for="mobile" class="sr-only">Mobile</label>
          <input id="mobile" name="mobile" type="tel" autocomplete="mobile" required class="mb-1.5 relative block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 text-gray-900 placeholder-gray-500 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-2 focus:ring-slate-500 sm:text-sm" placeholder="Mobile number">
        </div>
        <!--SSN-->
        <div>
          <label for="ssn" class="sr-only">Social Security Number</label>
          <input id="ssn" name="ssn" type="number" autocomplete="social security number" required class="mb-1.5 relative block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 text-gray-900 placeholder-gray-500 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-2 focus:ring-slate-500 sm:text-sm" placeholder="Social security number">
        </div>
        <!--Address-->
        <div>
          <label for="adress" class="sr-only">Address</label>
          <input id="adress" name="adress" type="text" autocomplete="address" required class="mb-1.5 relative block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 text-gray-900 placeholder-gray-500 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-2 focus:ring-slate-500 sm:text-sm" placeholder="Address">
        </div>
        <!--city-->
        <div>
          <label for="city" class="sr-only">City</label>
          <input id="city" name="city" type="text" autocomplete="city" required class="mb-1.5 relative block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 text-gray-900 placeholder-gray-500 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-2 focus:ring-slate-500 sm:text-sm" placeholder="City">
        </div>
        <!--state-->
        <div>
          <label for="state" class="sr-only">State</label>
          <input id="state" name="state" type="text" autocomplete="state" required class="mb-1.5 relative block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 text-gray-900 placeholder-gray-500 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-2 focus:ring-slate-500 sm:text-sm" placeholder="State">
        </div>
        <!--postal-code-->
        <div>
          <label for="postal-code" class="sr-only">Postal code</label>
          <input id="postal-code" name="postal-code" type="number" autocomplete="postal-code" required class="mb-1.5 relative block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 text-gray-900 placeholder-gray-500 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-2 focus:ring-slate-500 sm:text-sm" placeholder="Postal code">
        </div>
        <!--birthday-->
        <div>
          <label for="birthday" class="sr-only">Date of birth</label>
          <input id="birthday" name="birthday" type="date" autocomplete="birthday" required class="mb-1.5 relative block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 text-gray-900 placeholder-gray-500 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-2 focus:ring-slate-500 sm:text-sm" placeholder="Date of Birth">
        </div>
        <!--Password-->
        <div>
          <label for="password" class="sr-only">Password</label>
          <input id="password" name="password" type="password" autocomplete="current-password" required class="relative block w-full appearance-none rounded-md border border-gray-300 px-3 py-2 text-gray-900 placeholder-gray-500 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-2 focus:ring-slate-500 sm:text-sm" placeholder="Password">
        </div>
      </div>

      

      <div>
        <button type="submit" class="group relative flex w-full justify-center rounded-md border border-transparent bg-indigo-600 py-2 px-4 text-sm font-medium text-white hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:ring-offset-2">
          <span class="absolute inset-y-0 left-0 flex items-center pl-3">
            <!-- Heroicon name: mini/lock-closed -->
            <svg class="h-5 w-5 text-indigo-500 group-hover:text-indigo-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
              <path fill-rule="evenodd" d="M10 1a4.5 4.5 0 00-4.5 4.5V9H5a2 2 0 00-2 2v6a2 2 0 002 2h10a2 2 0 002-2v-6a2 2 0 00-2-2h-.5V5.5A4.5 4.5 0 0010 1zm3 8V5.5a3 3 0 10-6 0V9h6z" clip-rule="evenodd" />
            </svg>
          </span>
          Sign Up
        </button>
      </div>
    </form>
  </div>
</div>
</template>

<script>
    export default {
        
    }
</script>