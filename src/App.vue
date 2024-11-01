<script setup>
import FormInput from './components/FormInput.vue'
import LoginButton from './components/LoginButton.vue'

const handleSubmit = () => {
  console.log('Form submitted')
}
</script>

<template>
  <main class="flex justify-center h-screen items-center w-full">
    <div class="hidden sm:block">
      <img src="/home-phones.png" alt="Home Phones" />
    </div>
    <div class="flex flex-col justify-center gap-2 items-start">
      <section
        class="flex flex-col rounded-lg border border-gray-300 px-10 py-4"
      >
        <div
          class="text-5xl font-satisfy font-semibold tracking-tighter px-12 py-12"
        >
          Instagram
        </div>
        <div>
          <FormInput placeholder="Phone number, username, or email" />
          <FormInput placeholder="Password" />
        </div>
        <div class="flex py-4">
          <LoginButton @click="handleSubmit">Log in</LoginButton>
        </div>
        <p
          class="flex py-4 px-25 text-sm text-gray-500 items-center justify-center"
        >
          OR
        </p>
        <div class="flex gap-3 py-4 cursor-pointer item-center justify-center">
          <img src="/facebook.png" class="w-3.5" />
          <p class="text-blue-800 font-semibold">Log in with Facebook</p>
        </div>
        <p class="py-4 scale-75 cursor-pointer text-blue-950 text-center">
          Forgot password?
        </p>
      </section>
      <section
        class="flex gap-1 rounded-lg border border-gray-300 px-10 py-4 item-center justify-center w-full"
      >
        <div>Don't have an account?</div>
        <div class="text-sky-400">Sign up</div>
      </section>
      <p class="flex items-center justify-center w-full scale-90">
        Get the app.
      </p>
      <div class="flex items-center justify-center w-full gap-2">
        <img src="/Playstore.png" class="w-36" />
        <img src="/Microsoft.png" class="w-32" />
      </div>
    </div>
  </main>
  <footer
    class="flex flex-col text-sm w-full items-center justify-center text-gray-500 scale-90 py-10"
  >
    <div class="flex flex-wrap gap-6 py-4 cursor-pointer">
      <a href="#" class="hover:underline">Meta</a>
      <a href="#" class="hover:underline">About</a>
      <a href="#" class="hover:underline">Blog</a>
      <a href="#" class="hover:underline">Jobs</a>
      <a href="#" class="hover:underline">Help</a>
      <a href="#" class="hover:underline">API</a>
      <a href="#" class="hover:underline">Privacy</a>
      <a href="#" class="hover:underline">Terms</a>
      <a href="#" class="hover:underline">Locations</a>
      <a href="#" class="hover:underline">Instagram Lite</a>
      <a href="#" class="hover:underline">Threads</a>
      <a href="#" class="hover:underline">Contact Uploading & Non-Users</a>
      <a href="#" class="hover:underline">Meta Verified</a>
    </div>

    <div class="flex gap-2 py-1 items-center">
      <select
        name="language"
        id="language"
        class="border border-gray-300 rounded p-1"
      >
        <option value="en">English</option>
        <option value="es">Español</option>
        <option value="fr">Français</option>
        <option value="de">Deutsch</option>
        <option value="it">Italiano</option>
        <option value="pt">Português</option>
        <option value="zh">中文</option>
        <option value="ja">日本語</option>
        <option value="ko">한국어</option>
        <option value="ko">한국어</option>
        <option value="ru">Русский</option>
        <option value="ar">العربية</option>
        <option value="en-GB">English (UK)</option>
        <option value="hi">हिन्दी</option>
        <option value="ur">اردو</option>
        <option value="fa">فارسی</option>
        <option value="he">עברית</option>
        <option value="el">Ελληνικά</option>
        <option value="sv">Svenska</option>
        <option value="no">Norsk</option>
        <option value="da">Dansk</option>
        <option value="fi">Suomi</option>
        <option value="pl">Polski</option>
        <option value="cs">Čeština</option>
        <option value="hu">Magyar</option>
        <option value="ro">Română</option>
        <option value="sk">Slovenčina</option>
        <option value="bg">Български</option>
        <option value="uk">Українська</option>
        <option value="sr">Српски</option>
        <option value="hr">Hrvatski</option>
        <option value="sl">Slovenščina</option>
        <option value="lt">Lietuvių</option>
        <option value="lv">Latviešu</option>
        <option value="et">Eesti</option>
        <option value="tl">Filipino</option>
        <option value="id">Bahasa Indonesia</option>
        <option value="my">မြန်မာ</option>
        <option value="km">ភាសាខ្មែរ</option>
        <option value="lo">ພາສາລາວ</option>
        <option value="si">සිංහල</option>
        <option value="ta">தமிழ்</option>
        <option value="te">తెలుగు</option>
        <option value="ml">മലയാളം</option>
        <option value="kn">ಕನ್ನಡ</option>
        <option value="gu">ગુજરાતી</option>
        <option value="mr">मराठी</option>
        <option value="ne">नेपाली</option>
        <option value="am">አማርኛ</option>
        <option value="sw">Kiswahili</option>
        <option value="yo">Yorùbá</option>
        <option value="ig">Igbo</option>
        <option value="ha">Hausa</option>
        <option value="zu">isiZulu</option>
        <option value="xh">isiXhosa</option>
        <option value="af">Afrikaans</option>
        <option value="bn">বাংলা</option>
        <option value="pa">ਪੰਜਾਬੀ</option>
        <option value="jv">Basa Jawa</option>
        <option value="ms">Bahasa Melayu</option>
        <option value="vi">Tiếng Việt</option>
        <option value="th">ไทย</option>
        <option value="tr">Türkçe</option>
      </select>
      <span>&copy; 2024 Instagram from Meta</span>
    </div>
  </footer>
</template>
