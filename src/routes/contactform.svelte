<script>
    import { Button } from 'flowbite-svelte';
    import { Datepicker } from "flowbite-svelte";
  </script>
<div  class="p-16">
  <h1>Let's Get Started</h1>
<!-- <form  method="POST" use:enhance> -->
    <form>
    <div class="grid gap-6 mb-6 md:grid-cols-2">
        <div>
            <label for="fullname" class="text-sm font-medium block text-gray-900 dark:text-gray-300 mb-2">Full Name</label>
            <input
                id="fullname"
                placeholder="John"
                required=""
                class="block w-full disabled:cursor-not-allowed disabled:opacity-50 focus:border-primary-500 focus:ring-primary-500 dark:focus:border-primary-500 dark:focus:ring-primary-500 bg-gray-50 text-gray-900 dark:bg-gray-700 dark:text-white dark:placeholder-gray-400 border-gray-300 dark:border-gray-600 p-2.5 text-sm rounded-lg"
                type="text"
            />
        </div>

      
        <div>
            <label for="phoneNumber" class="text-sm font-medium block text-gray-900 dark:text-gray-300 mb-2">Phone Number</label>
            <input
                id="phonenumber"
                placeholder="Phone Number"
                required=""
                class="block w-full disabled:cursor-not-allowed disabled:opacity-50 focus:border-primary-500 focus:ring-primary-500 dark:focus:border-primary-500 dark:focus:ring-primary-500 bg-gray-50 text-gray-900 dark:bg-gray-700 dark:text-white dark:placeholder-gray-400 border-gray-300 dark:border-gray-600 p-2.5 text-sm rounded-lg"
                type="text"
            />
        </div>

        <div>
            <label for="email" class="text-sm font-medium block text-gray-900 dark:text-gray-300 mb-2">Email address</label>
            <input
                id="email"
                placeholder="john.doe@company.com"
              required
                class="block w-full disabled:cursor-not-allowed disabled:opacity-50 focus:border-primary-500 focus:ring-primary-500 dark:focus:border-primary-500 dark:focus:ring-primary-500 bg-gray-50 text-gray-900 dark:bg-gray-700 dark:text-white dark:placeholder-gray-400 border-gray-300 dark:border-gray-600 p-2.5 text-sm rounded-lg"
                type="email"
            />
        </div>
      
        <div>
            <label for="Guestcount" class="text-sm font-medium block text-gray-900 dark:text-gray-300 mb-2">Guest count</label>
            <input
                id="Guestcount"
                placeholder="Guest count"
                class="block w-full disabled:cursor-not-allowed disabled:opacity-50 focus:border-primary-500 focus:ring-primary-500 dark:focus:border-primary-500 dark:focus:ring-primary-500 bg-gray-50 text-gray-900 dark:bg-gray-700 dark:text-white dark:placeholder-gray-400 border-gray-300 dark:border-gray-600 p-2.5 text-sm rounded-lg"
                type="number"
            />
        </div>

        <div>
            <label for="budget" class="text-sm font-medium block text-gray-900 dark:text-gray-300 mb-2">Budget</label>
            <input
                id="budget"
                placeholder="Budget"
                class="block w-full disabled:cursor-not-allowed disabled:opacity-50 focus:border-primary-500 focus:ring-primary-500 dark:focus:border-primary-500 dark:focus:ring-primary-500 bg-gray-50 text-gray-900 dark:bg-gray-700 dark:text-white dark:placeholder-gray-400 border-gray-300 dark:border-gray-600 p-2.5 text-sm rounded-lg"
                type="number"
            />
        </div>

     

        <div>
            <label for="EventDate" class="text-sm font-medium block text-gray-900 dark:text-gray-300 mb-2">Event Date</label>
            <input
                id="EventDate"
                placeholder="Event Date"
                class="block w-full disabled:cursor-not-allowed disabled:opacity-50 focus:border-primary-500 focus:ring-primary-500 dark:focus:border-primary-500 dark:focus:ring-primary-500 bg-gray-50 text-gray-900 dark:bg-gray-700 dark:text-white dark:placeholder-gray-400 border-gray-300 dark:border-gray-600 p-2.5 text-sm rounded-lg"
                type="date"
            />
        </div>

        <div>
            <label for="venue" class="text-sm font-medium block text-gray-900 dark:text-gray-300 mb-2">Venue</label>
            <input
                id="venue"
                placeholder="Venue"
                class="block w-full disabled:cursor-not-allowed disabled:opacity-50 focus:border-primary-500 focus:ring-primary-500 dark:focus:border-primary-500 dark:focus:ring-primary-500 bg-gray-50 text-gray-900 dark:bg-gray-700 dark:text-white dark:placeholder-gray-400 border-gray-300 dark:border-gray-600 p-2.5 text-sm rounded-lg"
                type="date"
            />
        </div>

        <div>
            <label for="anythingelse" class="text-sm font-medium block text-gray-900 dark:text-gray-300 mb-2">Anthing else we should know?</label>
            <input
                id="anythingelse"
                placeholder="Anthing else we should know?"
                class="block w-full disabled:cursor-not-allowed disabled:opacity-50 focus:border-primary-500 focus:ring-primary-500 dark:focus:border-primary-500 dark:focus:ring-primary-500 bg-gray-50 text-gray-900 dark:bg-gray-700 dark:text-white dark:placeholder-gray-400 border-gray-300 dark:border-gray-600 p-2.5 text-sm rounded-lg"
                type="date"
            />
        </div>

    </div>
    <div class="mb-6">
        <!-- <Button>
            Submit Inquiry <svg aria-hidden="true" class="ml-2 -mr-1 w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
          </Button> -->

          <button type="submit" class="block w-full bg-indigo-600 mt-4 py-2 rounded-2xl text-white font-semibold mb-2"> Submit Inquiry </button>
    
    

    </div>
</form>
</div>