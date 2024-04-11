<template>
  <div class="portfolio">
    <div class="container relative z-20 flex flex-col w-full h-full px-6 gap:6 xl:gap-10 xl:flex-row">
      <div class="flex flex-col justify-between py-6 xl:max-w-sm xl:py-10 xl:h-full">
        <div>
          <div>
            <img class="avatar" alt="avatar" fetchpriority="high" loading="eager" width="200" height="250" decoding="async"
                 data-nimg="1"
                 style="color: transparent;"
                 srcset="../assets/IMG_6614.jpg"
                 src="../assets/IMG_6614.jpg">
          </div>
          <div class="mt-6">
            <div class="text-2xl font-medium text-primary">Developer</div>
            <h1 class="my-2 text-5xl font-bold">SAFAA WASSIM</h1>
            <p class="text-2xl font-light text-neutral-500">
              Je suis Safaa Wassim, étudiant en première année de licence en développement logiciel à l'Université de
              Haute Alsace 4.0 (UHA 4.0). Actuellement à la recherche d'opportunités de stage ou d'alternance pour
              l'année prochaine, je suis passionné par l'informatique et motivé pour acquérir une expérience pratique
              dans l'industrie du développement logiciel.
            </p>
          </div>
          <div class="flex items-center gap-3 mt-6">
            <a href="mailto:safaawassim01@gmail.com"
               class="flex items-center w-full gap-2 px-4 py-2 text-sm font-medium border rounded-md border-neutral-100 dark:border-neutral-800">
              <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none"
                   stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                   class="lucide lucide-mail">
                <rect width="20" height="16" x="2" y="4" rx="2"></rect>
                <path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"></path>
              </svg>
              Contact Me</a>
          </div>
        </div>
      </div>
      <div class="grid w-full grid-cols-4 xl:gap-10 gap-6 xl:py-10 py-6 xl:px-1 xl:overflow-y-auto auto-rows-[76px]">
        <div
            class="shadow-grid rounded-3xl bg-white dark:bg-neutral-900 flex flex-col justify-center @container md:col-span-1 col-span-2 row-span-2 md:p-8 p-4 hover:dark:bg-neutral-800 hover:bg-neutral-50 duration-75 transition-colors ease-in-out"
            style="opacity: 1; transform: none;"><a target="_blank" rel="noopener noreferrer"
                                                    href="https://github.com/Wassim-cyber39">
          <div class="flex items-center justify-between" style="opacity: 1; transform: none;">
            <div style="background-color: rgb(7, 7, 7); opacity: 1; transform: none;"
                 class="w-10 h-10 flex items-center justify-center rounded-lg shadow-grid shrink-0">
              <svg width="25" height="26" viewBox="0 0 25 26" fill="none" xmlns="http://www.w3.org/2000/svg">
                <g id="fa6-brands:github">
                  <path id="Vector"
                        d="M8.36417 20.1805C8.36417 20.282 8.24831 20.3633 8.10222 20.3633C7.93598 20.3785 7.82012 20.2973 7.82012 20.1805C7.82012 20.0789 7.93598 19.9977 8.08207 19.9977C8.23319 19.9824 8.36417 20.0637 8.36417 20.1805ZM6.7975 19.952C6.76223 20.0535 6.86298 20.1703 7.01411 20.2008C7.14509 20.2516 7.29621 20.2008 7.32644 20.0992C7.35666 19.9977 7.26095 19.8809 7.10982 19.8352C6.97885 19.7996 6.83276 19.8504 6.7975 19.952ZM9.02409 19.8656C8.878 19.9012 8.77725 19.9977 8.79236 20.1145C8.80747 20.216 8.93845 20.282 9.08958 20.2465C9.23566 20.2109 9.33641 20.1145 9.3213 20.0129C9.30619 19.9164 9.17018 19.8504 9.02409 19.8656ZM12.3388 0.40625C5.35172 0.40625 0.00689697 5.75352 0.00689697 12.7969C0.00689697 18.4285 3.5231 23.2477 8.54552 24.9438C9.19033 25.0605 9.41702 24.6594 9.41702 24.3293C9.41702 24.0145 9.4019 22.2777 9.4019 21.2113C9.4019 21.2113 5.87563 21.973 5.13511 19.698C5.13511 19.698 4.56083 18.2203 3.73467 17.8395C3.73467 17.8395 2.58108 17.0422 3.81527 17.0574C3.81527 17.0574 5.06962 17.159 5.75976 18.3676C6.86298 20.3277 8.71176 19.7641 9.43213 19.4289C9.54799 18.6164 9.87543 18.0527 10.2381 17.7176C7.42215 17.4027 4.58098 16.9914 4.58098 12.1062C4.58098 10.7098 4.96383 10.009 5.76984 9.11523C5.63886 8.78516 5.21067 7.42422 5.90082 5.66719C6.95366 5.33711 9.37672 7.03828 9.37672 7.03828C10.3842 6.75391 11.4673 6.60664 12.5403 6.60664C13.6133 6.60664 14.6964 6.75391 15.7039 7.03828C15.7039 7.03828 18.1269 5.33203 19.1798 5.66719C19.8699 7.4293 19.4417 8.78516 19.3107 9.11523C20.1167 10.0141 20.6104 10.7148 20.6104 12.1062C20.6104 17.0066 17.6433 17.3977 14.8273 17.7176C15.2908 18.1187 15.6837 18.8805 15.6837 20.0738C15.6837 21.7852 15.6686 23.9027 15.6686 24.3191C15.6686 24.6492 15.9003 25.0504 16.5401 24.9336C21.5776 23.2477 24.9931 18.4285 24.9931 12.7969C24.9931 5.75352 19.3259 0.40625 12.3388 0.40625ZM4.90338 17.9207C4.83789 17.9715 4.85301 18.0883 4.93865 18.1848C5.01925 18.266 5.13511 18.3016 5.2006 18.2355C5.26609 18.1848 5.25097 18.068 5.16533 17.9715C5.08473 17.8902 4.96887 17.8547 4.90338 17.9207ZM4.35933 17.5094C4.32407 17.5754 4.37444 17.6566 4.47519 17.7074C4.55579 17.7582 4.65654 17.743 4.69181 17.6719C4.72707 17.6059 4.67669 17.5246 4.57594 17.4738C4.47519 17.4434 4.39459 17.4586 4.35933 17.5094ZM5.99149 19.3172C5.91089 19.3832 5.94112 19.5355 6.05698 19.632C6.17284 19.7488 6.31893 19.7641 6.38442 19.6828C6.44991 19.6168 6.41968 19.4645 6.31893 19.368C6.2081 19.2512 6.05698 19.2359 5.99149 19.3172ZM5.41721 18.5707C5.33661 18.6215 5.33661 18.7535 5.41721 18.8703C5.49781 18.9871 5.63383 19.0379 5.69931 18.9871C5.77991 18.9211 5.77991 18.7891 5.69931 18.6723C5.62879 18.5555 5.49781 18.5047 5.41721 18.5707Z"
                        fill="white"></path>
                </g>
              </svg>
            </div>
          </div>
          <div class="mt-2" style="opacity: 1; transform: none;">
            <div class="@lg:text-lg font-semibold line-clamp-1" style="opacity: 1; transform: none;">Github</div>
            <div class="text-sm text-neutral-500" style="opacity: 1; transform: none;">@Wassim-cyber39</div>
            <div class="mt-2" style="opacity: 1; transform: none;">
              <div style="background-color: rgb(7, 7, 7); opacity: 1; transform: none;"
                   class="flex items-center gap-2 px-3 py-1 text-sm font-medium text-white rounded-lg max-w-fit"><span>Follow</span>
              </div>
            </div>
          </div>
        </a></div>
        <div
            class="shadow-grid rounded-3xl bg-white dark:bg-neutral-900 flex flex-col justify-center @container md:col-span-1 col-span-2 row-span-2 md:p-8 p-4 hover:dark:bg-neutral-800 hover:bg-neutral-50 duration-75 transition-colors ease-in-out"
            style="opacity: 1; transform: none;"><a target="_blank" rel="noopener noreferrer"
                                                    href="https://www.linkedin.com/in/wassim-safaa-8380b426a/">
          <div class="flex items-center justify-between" style="opacity: 1; transform: none;">
            <div style="background-color: rgb(10, 102, 194); opacity: 1; transform: none;"
                 class="w-10 h-10 flex items-center justify-center rounded-lg shadow-grid shrink-0">
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                   stroke="#fff"
                   stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-linkedin">
                <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path>
                <rect width="4" height="12" x="2" y="9"></rect>
                <circle cx="4" cy="4" r="2"></circle>
              </svg>
            </div>
          </div>
          <div class="mt-2" style="opacity: 1; transform: none;">
            <div class="@lg:text-lg font-semibold line-clamp-1" style="opacity: 1; transform: none;">Linkedin</div>
            <div class="text-sm text-neutral-500" style="opacity: 1; transform: none;">@Wassim</div>
            <div class="mt-2" style="opacity: 1; transform: none;">
              <div style="background-color: rgb(10, 102, 194); opacity: 1; transform: none;"
                   class="flex items-center gap-2 px-3 py-1 text-sm font-medium text-white rounded-lg max-w-fit"><span>Follow</span>
              </div>
            </div>
          </div>
        </a></div>
        <div class="shadow-grid rounded-3xl bg-white dark:bg-neutral-900 flex flex-col justify-center @container md:col-span-1 col-span-2 row-span-2 md:p-8 p-4 hover:dark:bg-neutral-800 hover:bg-neutral-50 duration-75 transition-colors ease-in-out" style="opacity: 1; transform: none;">
          <a href="../assets/CV_alternance.pdf" download>
          <div class="flex items-center justify-between" style="opacity: 1; transform: none;">
              <div style="background-color: rgb(7, 7, 7); opacity: 1; transform: none;" class="w-10 h-10 flex items-center justify-center rounded-lg shadow-grid shrink-0">
                <svg width="25" height="26" viewBox="0 0 25 26" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <g id="fa6-brands:github">
                    <path id="Vector" d="M8.36417 20.1805C8.36417 20.282 8.24831 20.3633 8.10222 20.3633C7.93598 20.3785 7.82012 20.2973 7.82012 20.1805C7.82012 20.0789 7.93598 19.9977 8.08207 19.9977C8.23319 19.9824 8.36417 20.0637 8.36417 20.1805ZM6.7975 19.952C6.76223 20.0535 6.86298 20.1703 7.01411 20.2008C7.14509 20.2516 7.29621 20.2008 7.32644 20.0992C7.35666 19.9977 7.26095 19.8809 7.10982 19.8352C6.97885 19.7996 6.83276 19.8504 6.7975 19.952ZM9.02409 19.8656C8.878 19.9012 8.77725 19.9977 8.79236 20.1145C8.80747 20.216 8.93845 20.282 9.08958 20.2465C9.23566 20.2109 9.33641 20.1145 9.3213 20.0129C9.30619 19.9164 9.17018 19.8504 9.02409 19.8656ZM12.3388 0.40625C5.35172 0.40625 0.00689697 5.75352 0.00689697 12.7969C0.00689697 18.4285 3.5231 23.2477 8.54552 24.9438C9.19033 25.0605 9.41702 24.6594 9.41702 24.3293C9.41702 24.0145 9.4019 22.2777 9.4019 21.2113C9.4019 21.2113 5.87563 21.973 5.13511 19.698C5.13511 19.698 4.56083 18.2203 3.73467 17.8395C3.73467 17.8395 2.58108 17.0422 3.81527 17.0574C3.81527 17.0574 5.06962 17.159 5.75976 18.3676C6.86298 20.3277 8.71176 19.7641 9.43213 19.4289C9.54799 18.6164 9.87543 18.0527 10.2381 17.7176C7.42215 17.4027 4.58098 16.9914 4.58098 12.1062C4.58098 10.7098 4.96383 10.009 5.76984 9.11523C5.63886 8.78516 5.21067 7.42422 5.90082 5.66719C6.95366 5.33711 9.37672 7.03828 9.37672 7.03828C10.3842 6.75391 11.4673 6.60664 12.5403 6.60664C13.6133 6.60664 14.6964 6.75391 15.7039 7.03828C15.7039 7.03828 18.1269 5.33203 19.1798 5.66719C19.8699 7.4293 19.4417 8.78516 19.3107 9.11523C20.1167 10.0141 20.6104 10.7148 20.6104 12.1062C20.6104 17.0066 17.6433 17.3977 14.8273 17.7176C15.2908 18.1187 15.6837 18.8805 15.6837 20.0738C15.6837 21.7852 15.6686 23.9027 15.6686 24.3191C15.6686 24.6492 15.9003 25.0504 16.5401 24.9336C21.5776 23.2477 24.9931 18.4285 24.9931 12.7969C24.9931 5.75352 19.3259 0.40625 12.3388 0.40625ZM4.90338 17.9207C4.83789 17.9715 4.85301 18.0883 4.93865 18.1848C5.01925 18.266 5.13511 18.3016 5.2006 18.2355C5.26609 18.1848 5.25097 18.068 5.16533 17.9715C5.08473 17.8902 4.96887 17.8547 4.90338 17.9207ZM4.35933 17.5094C4.32407 17.5754 4.37444 17.6566 4.47519 17.7074C4.55579 17.7582 4.65654 17.743 4.69181 17.6719C4.72707 17.6059 4.67669 17.5246 4.57594 17.4738C4.47519 17.4434 4.39459 17.4586 4.35933 17.5094ZM5.99149 19.3172C5.91089 19.3832 5.94112 19.5355 6.05698 19.632C6.17284 19.7488 6.31893 19.7641 6.38442 19.6828C6.44991 19.6168 6.41968 19.4645 6.31893 19.368C6.2081 19.2512 6.05698 19.2359 5.99149 19.3172ZM5.41721 18.5707C5.33661 18.6215 5.33661 18.7535 5.41721 18.8703C5.49781 18.9871 5.63383 19.0379 5.69931 18.9871C5.77991 18.9211 5.77991 18.7891 5.69931 18.6723C5.62879 18.5555 5.49781 18.5047 5.41721 18.5707Z" fill="white"></path>
                  </g>
                </svg>
              </div>
            </div>
            <div class="mt-2" style="opacity: 1; transform: none;">
              <div class="@lg:text-lg font-semibold line-clamp-1" style="opacity: 1; transform: none;">CV Alternance</div>
              <div class="mt-2" style="opacity: 1; transform: none;">
                <div style="background-color: rgb(7, 7, 7); opacity: 1; transform: none;" class="flex items-center gap-2 px-3 py-1 text-sm font-medium text-white rounded-lg max-w-fit"><span>Télécharger</span></div>
              </div>
            </div>
          </a>
        </div>

        <div class="shadow-grid rounded-3xl bg-white dark:bg-neutral-900 flex flex-col justify-center @container md:col-span-1 col-span-2 row-span-2 md:p-8 p-4 hover:dark:bg-neutral-800 hover:bg-neutral-50 duration-75 transition-colors ease-in-out" style="opacity: 1; transform: none;">
          <a href="../assets/CV_stage.pdf" download>Télécharger CV Stage</a>
          <a href="../assets/CV_stage.pdf" download>Télécharger CV Stage
          <div class="flex items-center justify-between" style="opacity: 1; transform: none;">
              <div style="background-color: rgb(7, 7, 7); opacity: 1; transform: none;" class="w-10 h-10 flex items-center justify-center rounded-lg shadow-grid shrink-0">
                <svg width="25" height="26" viewBox="0 0 25 26" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <g id="fa6-brands:github">
                    <path id="Vector" d="M8.36417 20.1805C8.36417 20.282 8.24831 20.3633 8.10222 20.3633C7.93598 20.3785 7.82012 20.2973 7.82012 20.1805C7.82012 20.0789 7.93598 19.9977 8.08207 19.9977C8.23319 19.9824 8.36417 20.0637 8.36417 20.1805ZM6.7975 19.952C6.76223 20.0535 6.86298 20.1703 7.01411 20.2008C7.14509 20.2516 7.29621 20.2008 7.32644 20.0992C7.35666 19.9977 7.26095 19.8809 7.10982 19.8352C6.97885 19.7996 6.83276 19.8504 6.7975 19.952ZM9.02409 19.8656C8.878 19.9012 8.77725 19.9977 8.79236 20.1145C8.80747 20.216 8.93845 20.282 9.08958 20.2465C9.23566 20.2109 9.33641 20.1145 9.3213 20.0129C9.30619 19.9164 9.17018 19.8504 9.02409 19.8656ZM12.3388 0.40625C5.35172 0.40625 0.00689697 5.75352 0.00689697 12.7969C0.00689697 18.4285 3.5231 23.2477 8.54552 24.9438C9.19033 25.0605 9.41702 24.6594 9.41702 24.3293C9.41702 24.0145 9.4019 22.2777 9.4019 21.2113C9.4019 21.2113 5.87563 21.973 5.13511 19.698C5.13511 19.698 4.56083 18.2203 3.73467 17.8395C3.73467 17.8395 2.58108 17.0422 3.81527 17.0574C3.81527 17.0574 5.06962 17.159 5.75976 18.3676C6.86298 20.3277 8.71176 19.7641 9.43213 19.4289C9.54799 18.6164 9.87543 18.0527 10.2381 17.7176C7.42215 17.4027 4.58098 16.9914 4.58098 12.1062C4.58098 10.7098 4.96383 10.009 5.76984 9.11523C5.63886 8.78516 5.21067 7.42422 5.90082 5.66719C6.95366 5.33711 9.37672 7.03828 9.37672 7.03828C10.3842 6.75391 11.4673 6.60664 12.5403 6.60664C13.6133 6.60664 14.6964 6.75391 15.7039 7.03828C15.7039 7.03828 18.1269 5.33203 19.1798 5.66719C19.8699 7.4293 19.4417 8.78516 19.3107 9.11523C20.1167 10.0141 20.6104 10.7148 20.6104 12.1062C20.6104 17.0066 17.6433 17.3977 14.8273 17.7176C15.2908 18.1187 15.6837 18.8805 15.6837 20.0738C15.6837 21.7852 15.6686 23.9027 15.6686 24.3191C15.6686 24.6492 15.9003 25.0504 16.5401 24.9336C21.5776 23.2477 24.9931 18.4285 24.9931 12.7969C24.9931 5.75352 19.3259 0.40625 12.3388 0.40625ZM4.90338 17.9207C4.83789 17.9715 4.85301 18.0883 4.93865 18.1848C5.01925 18.266 5.13511 18.3016 5.2006 18.2355C5.26609 18.1848 5.25097 18.068 5.16533 17.9715C5.08473 17.8902 4.96887 17.8547 4.90338 17.9207ZM4.35933 17.5094C4.32407 17.5754 4.37444 17.6566 4.47519 17.7074C4.55579 17.7582 4.65654 17.743 4.69181 17.6719C4.72707 17.6059 4.67669 17.5246 4.57594 17.4738C4.47519 17.4434 4.39459 17.4586 4.35933 17.5094ZM5.99149 19.3172C5.91089 19.3832 5.94112 19.5355 6.05698 19.632C6.17284 19.7488 6.31893 19.7641 6.38442 19.6828C6.44991 19.6168 6.41968 19.4645 6.31893 19.368C6.2081 19.2512 6.05698 19.2359 5.99149 19.3172ZM5.41721 18.5707C5.33661 18.6215 5.33661 18.7535 5.41721 18.8703C5.49781 18.9871 5.63383 19.0379 5.69931 18.9871C5.77991 18.9211 5.77991 18.7891 5.69931 18.6723C5.62879 18.5555 5.49781 18.5047 5.41721 18.5707Z" fill="white"></path>
                  </g>
                </svg>
              </div>
            </div>
            <div class="mt-2" style="opacity: 1; transform: none;">
              <div class="@lg:text-lg font-semibold line-clamp-1" style="opacity: 1; transform: none;">CV Stage</div>
              <div class="mt-2" style="opacity: 1; transform: none;">
                <div style="background-color: rgb(7, 7, 7); opacity: 1; transform: none;" class="flex items-center gap-2 px-3 py-1 text-sm font-medium text-white rounded-lg max-w-fit"><span>Télécharger</span></div>
              </div>
            </div>
          </a>
        </div>


        <div
            class="shadow-grid rounded-3xl bg-white dark:bg-neutral-900 flex flex-col justify-center @container md:col-span-2 col-span-full row-span-4 relative overflow-hidden hover:dark:bg-neutral-800 hover:bg-neutral-50 duration-75 transition-colors ease-in-out"
            style="opacity: 1; transform: none;"><a target="_blank" rel="noopener noreferrer"
                                                    href="https://avocadogrowth.com">
          <div class="flex cursor-pointer flex-col items-end justify-end w-full h-full overflow-hidden rounded-3xl"
               style="opacity: 1; transform: none;">
            <div class="absolute inset-0 z-10 bg-gradient-to-b from-transparent via-neutral-950/60 to-neutral-950/90"
                 style="opacity: 1; transform: none;"></div>
            <img alt="equipments" loading="lazy" decoding="async" data-nimg="fill"
                 class="z-0 object-cover object-center w-full h-full"
                 style="position:absolute;height:100%;width:100%;left:0;top:0;right:0;bottom:0;color:transparent"
                 sizes="100vw"
                 srcset=""
                 src="">
            <div class="relative z-20 w-full p-4 space-y-3 md:p-8" style="opacity: 1; transform: none;">
              <div class="text-sm font-medium text-white" style="opacity: 1; transform: none;">Avocado Growth</div>
              <div class="flex flex-wrap items-center gap-3" style="opacity: 1; transform: none;"><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Next JS</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Tailwind CSS</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">ShadCn UI</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Supabase</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">TypeScript</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Vercel</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Stripe</span></div>
            </div>
          </div>
        </a></div>
        <div
            class="shadow-grid rounded-3xl bg-white dark:bg-neutral-900 flex flex-col justify-center @container md:col-span-2 col-span-full row-span-4 relative overflow-hidden hover:dark:bg-neutral-800 hover:bg-neutral-50 duration-75 transition-colors ease-in-out"
            style="opacity: 1; transform: none;"><a target="_blank" rel="noopener noreferrer"
                                                    href="https://coding-challenge.avocadogrowth.com/en">
          <div class="flex cursor-pointer flex-col items-end justify-end w-full h-full overflow-hidden rounded-3xl"
               style="opacity: 1; transform: none;">
            <div class="absolute inset-0 z-10 bg-gradient-to-b from-transparent via-neutral-950/60 to-neutral-950/90"
                 style="opacity: 1; transform: none;"></div>
            <img alt="equipments" loading="lazy" decoding="async" data-nimg="fill"
                 class="z-0 object-cover object-center w-full h-full"
                 style="position:absolute;height:100%;width:100%;left:0;top:0;right:0;bottom:0;color:transparent"
                 sizes="100vw"
                 srcset=""
                 src="">
            <div class="relative z-20 w-full p-4 space-y-3 md:p-8" style="opacity: 1; transform: none;">
              <div class="text-sm font-medium text-white" style="opacity: 1; transform: none;">Coding Challenge</div>
              <div class="flex flex-wrap items-center gap-3" style="opacity: 1; transform: none;"><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Next JS</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Tailwind CSS</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">ShadCn UI</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">PostgreSQL</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">TypeScript</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Vercel</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Stripe</span></div>
            </div>
          </div>
        </a></div>
        <div
            class="shadow-grid rounded-3xl bg-white dark:bg-neutral-900 flex flex-col justify-center @container md:col-span-2 col-span-full row-span-4 relative overflow-hidden hover:dark:bg-neutral-800 hover:bg-neutral-50 duration-75 transition-colors ease-in-out"
            style="opacity: 1; transform: none;"><a target="_blank" rel="noopener noreferrer"
                                                    href="https://interviewmentorai.com/">
          <div class="flex cursor-pointer flex-col items-end justify-end w-full h-full overflow-hidden rounded-3xl"
               style="opacity: 1; transform: none;">
            <div class="absolute inset-0 z-10 bg-gradient-to-b from-transparent via-neutral-950/60 to-neutral-950/90"
                 style="opacity: 1; transform: none;"></div>
            <img alt="equipments" loading="lazy" decoding="async" data-nimg="fill"
                 class="z-0 object-cover object-center w-full h-full"
                 style="position:absolute;height:100%;width:100%;left:0;top:0;right:0;bottom:0;color:transparent"
                 sizes="100vw"
                 srcset=""
                 src="/">
            <div class="relative z-20 w-full p-4 space-y-3 md:p-8" style="opacity: 1; transform: none;">
              <div class="text-sm font-medium text-white" style="opacity: 1; transform: none;">Interview Mentor AI</div>
              <div class="flex flex-wrap items-center gap-3" style="opacity: 1; transform: none;"><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Next JS</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Tailwind CSS</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">ShadCn UI</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Supabase</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">TypeScript</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Vercel</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Stripe</span></div>
            </div>
          </div>
        </a></div>
        <div
            class="shadow-grid rounded-3xl bg-white dark:bg-neutral-900 flex flex-col justify-center @container md:col-span-2 col-span-full row-span-4 relative overflow-hidden hover:dark:bg-neutral-800 hover:bg-neutral-50 duration-75 transition-colors ease-in-out"
            style="opacity: 1; transform: none;"><a target="_blank" rel="noopener noreferrer"
                                                    href="https://www.skillsupapp.com">
          <div class="flex cursor-pointer flex-col items-end justify-end w-full h-full overflow-hidden rounded-3xl"
               style="opacity: 1; transform: none;">
            <div class="absolute inset-0 z-10 bg-gradient-to-b from-transparent via-neutral-950/60 to-neutral-950/90"
                 style="opacity: 1; transform: none;"></div>
            <img alt="equipments" loading="lazy" decoding="async" data-nimg="fill"
                 class="z-0 object-cover object-center w-full h-full"
                 style="position:absolute;height:100%;width:100%;left:0;top:0;right:0;bottom:0;color:transparent"
                 sizes="100vw"
                 srcset=""
                 src="">
            <div class="relative z-20 w-full p-4 space-y-3 md:p-8" style="opacity: 1; transform: none;">
              <div class="text-sm font-medium text-white" style="opacity: 1; transform: none;">Skills UP</div>
              <div class="flex flex-wrap items-center gap-3" style="opacity: 1; transform: none;"><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Next JS</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Tailwind CSS</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">ShadCn UI</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Supabase</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">TypeScript</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Vercel</span><span
                  class="px-2 py-1 text-sm font-medium bg-[#4F6F52] rounded-lg ">Stripe</span></div>
            </div>
          </div>
        </a></div>
      </div>
      <div class="flex pb-6 xl:hidden">
        <div class="flex items-center justify-center w-full pt-6 border-t border-neutral-100 dark:border-neutral-800">
          <div class="container flex items-center justify-between">
            <button class="relative inline-flex">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none"
                   stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                   class="transition-all scale-100 rotate-0 dark:-rotate-90 dark:scale-0">
                <circle cx="12" cy="12" r="4"></circle>
                <path d="M12 2v2"></path>
                <path d="M12 20v2"></path>
                <path d="m4.93 4.93 1.41 1.41"></path>
                <path d="m17.66 17.66 1.41 1.41"></path>
                <path d="M2 12h2"></path>
                <path d="M20 12h2"></path>
                <path d="m6.34 17.66-1.41 1.41"></path>
                <path d="m19.07 4.93-1.41 1.41"></path>
              </svg>
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none"
                   stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                   class="absolute transition-all scale-0 rotate-90 dark:rotate-0 dark:scale-100">
                <path d="M12 3a6 6 0 0 0 9 9 9 9 0 1 1-9-9Z"></path>
              </svg>
              <span class="sr-only">Toggle theme</span>
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>


.portfolio {
  background: black;
  color: white;
}
.avatar {
  border-radius: 40%;
  overflow: hidden;
}
</style>
