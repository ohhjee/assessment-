<template>
  <div class="grid grid-cols-2">
    <div class="bg-[#F8EAFF] min-h-screen col-span-1 w-full p-4 hidden  lg:flex items-start justify-center flex-col">
      <div class="container mx-auto px-[2rem]">
        <div class="h-[10vh] w-[20vh]">
          <img
            src="../assets/image/image 30.png"
            class="w-full h-full"
            alt=""
          />
        </div>
        <!-- TEAM ACHIEVE IMAGE -->
        <div class="mt-[2rem] space-y-5">
          <div>
            <img src="../assets/image/image 31.png" class="w-full" alt="" />
          </div>
          <!-- TEAM TEXT -->
          <div class="text-center">
            <div class="text-[#61227D] font-bold text-[1.25rem]">
              Team Achieve
            </div>
            <div class="text-[#5E5E5E] text-[1rem] font-bold">
              Your perfect solution for funding your desires
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="col-span-2 lg:col-span-1">
      <div class=" min-h-screen flex w-11/12 md:w-10/12 mx-auto justify-center flex-col">
        <div class="md:hidden mb-3 flex items-start justify-center">
            <div class="h-[20vh] w-[40vh]">
                <img
                  src="../assets/image/image 30.png"
                  class="w-full h-full"
                  alt=""
                />
              </div>
        </div>
      <div class="">
        <!-- header -->
        <div class="space-y-2 text-center">
          <div class="text-[#61227D] font-bold text-[1.9rem]">Welcome back</div>
          <div class="text-[.875rem] md:text-[1rem] text-[#5E5E5E] font-normal ">
            Enter your email address and password to access your account.
          </div>
        </div>
        <!-- form section -->
        <div class="mt-[2rem]">
          <form class="space-y-6">
            <div class="space-y-1">
              <label for="email" class="block text-[1rem] font-normal"
                >Email Address <span class="text-red-500">*</span></label
              >
              <input
                type="email"
                class="border focus-within:outline-none w-full px-[.625rem] py-[.81rem] rounded-lg placeholder:text-[.8rem] placeholder:text-[ #DDDDDD]"
                placeholder="Enter your email"
              />
            </div>
            <div class="space-y-1">
              <label for="password" class="block text-[1rem] font-normal"
                >Password <span class="text-red-500">*</span></label
              >
              <div class="flex">
                <input
                  type="password"
                  class="border focus-within:outline-none w-full px-[.625rem] py-[.81rem] rounded-ss-lg rounded-es-lg placeholder:text-[.8rem] placeholder:text-[ #DDDDDD]"
                  placeholder="Enter your email"
                />
                <span
                  class="flex items-center justify-center border border-l-0 rounded-se-lg rounded-ee-lg w-[48px]"
                >
                  <Icon
                    icon="ph:eye"
                    width="24"
                    height="24"
                    style="color: #c6c6c6"
                  />
                </span>
              </div>
              <!-- forget-password & remember me -->
              <div class="flex justify-between items-center pt-[.5rem]">
                <div class="flex items-center">
                  <input type="checkbox" id="check" />
                  <label for="check" class="text-[#7D7D7D] text-[.875rem] ml-1">Remember me</label>
                </div>
                <div>
                    <a href="#" class="capitalize text-[#61227D] text-[.875rem]">forget password?</a>
                </div>
              </div>
            </div>
            <div>
                <button class="bg-[#61227D] w-full text-center text-white px-[.8rem] py-[.6rem] rounded-lg">sign in</button>
                <div class="text-center mt-[1rem]">
                    <div class="text-[.8rem]">Don't have an account?
                    <span class="text-[#6122dd] text-[.8rem] font-semibold">Sign up</span>
                    </div>
                </div>
            </div>
          </form>
        </div>
      </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Icon } from "@iconify/vue";

export default defineComponent({
  components: { Icon },
  setup() {
    return {};
  },
});
</script>

<style lang="scss" scoped></style>
