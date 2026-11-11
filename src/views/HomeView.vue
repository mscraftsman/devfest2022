<template>
  <main class="relative">
    <div class="max-w-6xl mx-auto mt-4 md:mt-8 mb-10 px-4 lg:px-0">
        <img src="/images/hero-2022.png" class="object-fit rounded-lg shadow-md mb-2 md:mb-8" />
        <h2 class="text-2xl md:text-3xl font-bold mb-3 md:mb-4">About GDG Mauritius</h2>
        <div class="flex flex-col md:flex-row">
            <div class="md:mr-6 md:w-1/2">
                <p class="mb-2 md:mb-4 text-sm md:text-lg">Google Developer Groups (GDG) - is an open and volunteer geek
                    community who create exciting projects and share their experience about Google technologies
                    with a passion.</p>
                <p class="mb-2 md:mb-4 text-sm md:text-lg">DevFest (Developers Festival) Mauritius is a single-day, two-track,
                    inclusive conference for all developers. It is an annual community-run event that offers
                    keynote speakers who are very influential, speaker sessions across multiple product
                    areas, including hack-a-thons, codelabs, and more.</p>
                <p class="text-lg mb-4">Come and join us at the DevFest 2022! Let's get together and end this year on a Google note!</p>

                <h2 class="text-2xl md:text-3xl font-bold mb-4">What you need to know</h2>
                <p class="mb-2 md:mb-4 text-sm md:text-lg">
                    We are so thrilled to be able to host DevFest Mauritius 2022 at the African Leadership College this year.
                </p>
                <p class="mb-2 md:mb-4 text-sm md:text-lg">
                    Although restrictions are lifted, we highly recommend everyone to take necessary precautions as
                    COVID is still present. Therefore please consider the following when attending the conference.
                </p>
                <ul class="list-disc list-inside text-sm md:text-lg mb-2 md:mb-4">
                    <li>Temperature check will be done before entering the campus</li>
                    <li>We recommend wearing a face mask </li>
                    <li>Social distancing is advisable</li>
                </ul>
                <p class="mb-2 md:mb-4 text-sm md:text-lg">
                    Thank you for your understanding!
                </p>
            </div>
            <div class="mt-4 md:mt-0 md:ml-6 md:w-1/2 grid grid-cols-2">
                <div class="w-1/2 flex flex-col">
                    <span class="text-4xl md:text-6xl font-bold border-b-4 border-green-600">200</span>
                    <span class="text-xl md:text-2xl">attendees</span>
                </div>
                <div class="w-1/2 flex flex-col">
                    <span class="text-4xl md:text-6xl font-bold border-b-4 border-green-600">1</span>
                    <span class="text-xl md:text-2xl">day</span>
                </div>
                <div class="mt-2 md:mt-0 w-1/2 flex flex-col">
                    <span class="text-4xl md:text-6xl font-bold border-b-4 border-green-600">12</span>
                    <span class="text-xl md:text-2xl">sessions</span>
                </div>
                <div class="mt-2 md:mt-0 w-1/2 flex flex-col">
                    <span class="text-4xl md:text-6xl font-bold border-b-4 border-green-600">2</span>
                    <span class="text-xl md:text-2xl">tracks</span>
                </div>
            </div>
        </div>

        <!-- Devfest 2022 video trailer -->
        <div class="mt-8 grid place-items-center">
            <h2 class="text-3xl font-bold text-green-600 mb-4">What's awaiting at DevFest 2022!</h2>
            <iframe class="rounded-md md:rounded-lg w-[100%] h-[100%] lg:w-[800px] md:h-[405px]" src="https://www.youtube.com/embed/K6W9Usve6hI?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>

        <!-- The Event -->
        <div class="mt-8 md:mt-20 flex flex-col md:flex-row">
            <div class="md:mr-2 lg:mr-6 md:w-1/2">
                <img class="rounded-md md:rounded-lg md:mt-2" src="/images/alc.jpeg" />
            </div>
            <div class="mt-6 md:mt-0 md:ml-2 lg:ml-6 md:w-1/2">
                <h2 class="text-2xl md:text-3xl font-bold mb-2 md:mb-4">The Event</h2>
                <p class="mb-2 md:mb-4 text-sm md:text-lg">
                    This is a gathering of developers and technology enthusiasts who will cover multiple product areas such as Android, Firebase, Kotlin, Flutter, Google Cloud Platform, ARCore, Google Assistant, Design Sprint, IoT, Machine Learning, Mobile Web and Artificial Intelligence.
                </p>
                <p class="mb-2 md:mb-4 text-sm md:text-lg">
                    Key sponsors will be present on that day. Do not hesitate to meet them at their booths to learn more about them. See what they have waiting for you 🙂.
                </p>
            </div>
        </div>

        <!-- Location map -->
        <div class="mt-8 md:mt-20 grid place-items-center">
            <iframe class="rounded-lg w-[100%] md:h-[405px]" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3746.7668730684636!2d57.56026181528462!3d-20.10202984887379!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x217c5522a5ca9c1f%3A0x3bdb9ec034be93fa!2sAfrican%20Leadership%20College!5e0!3m2!1sen!2smu!4v1669811589702!5m2!1sen!2smu" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>

        <!-- Partners -->
        <div class="grid place-items-center md:place-items-start">
            <h2 class="mt-8 md:mt-10 text-3xl font-bold">Partners</h2>
        </div>

        <div class="md:hidden sm:block lg:block">
            <div class="flex flex-col lg:flex-row md:gap-4 items-center">
                <img class="h-12 md:mr-4 mt-10 md:mt-0" src="/images/Google.svg" />
                <img class="h-32" src="/images/novity.jpg" />
                <img class="h-12" src="/images/sdworx.png" />
                <img class="h-12 md:ml-4 md:mr-6 mt-6 md:mt-0" src="/images/cloud-mu.svg" />
            </div>
            <div class="mt-6 flex flex-col lg:flex-row md:gap-4 items-center">
                <img class="h-12 mt-3 md:mt-0" src="/images/alc_logo.jpg" />
                <img class="h-28 mt-3 md:mt-0" src="/images/ios.png" />
            </div>
        </div>

        <div class="hidden md:block lg:hidden">
            <div class="flex flex-row gap-4 items-center">
                            <img class="h-12 md:mx-4 mt-10 md:mt-0" src="/images/Google.svg" />
							<img class="h-32" src="/images/novity.jpg" />
							<img class="h-32" src="/images/sdworx.svg" />
							<img class="h-12 md:ml-4 md:mr-6 mt-3 md:mt-0" src="/images/cloud-mu.svg" />
            </div>
            <div class="flex flex-row gap-4 items-center">
							<img class="h-12 mt-3 md:mt-0" src="/images/alc_logo.jpg" />
							<img class="h-32 mt-3 md:mt-0" src="/images/ios.png" />
            </div>
        </div>

				<SessionsComponent />
    </div>
  </main>
</template>

<script>
import SessionsComponent from '../components/SessionsComponent.vue';

export default {
	components: {
		SessionsComponent,
	}
}
</script>
