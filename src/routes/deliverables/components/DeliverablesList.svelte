<script>
  import DeliverableListItem from "./DeliverableListItem.svelte";
</script>

<div class="bg-white">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="lg:grid lg:grid-cols-3 lg:gap-8">
      <div>
        <img
          class="relative rounded-lg hidden lg:flex"
          src="https://images.unsplash.com/flagged/photo-1566838634584-c541648798ab?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=500&h=700&q=80"
          alt=""
        />
      </div>
      <div class="mt-12 lg:mt-0 lg:col-span-2">
        <div class="mb-8">
          <h2 class="text-3xl font-extrabold text-gray-900">Deliverables</h2>
          <p class="mt-4 text-lg text-gray-500">
            Each milestone is made of severeal deliverables that can be consulted everytime you
            wish.
          </p>
        </div>
        <div class="grid grid-cols-12">
          <DeliverableListItem title="Milestone 1">
            <a
              class="text-green-700 mb-1"
              href="https://drive.google.com/file/d/1EPgmVPdswY9SxuPNSz_BCZ-KvRkjpdUy/view?usp=sharing"
              target="_blank"
            >
              Presentation 1
            </a>
            <a
              class="text-green-700 mb-1"
              href="https://docs.google.com/document/d/1rS6B_iSGQombkqGmNwLuFXgrzOUVjk-Io423m0MZg5I/edit?usp=sharing"
              target="_blank"
            >
              Inception Report
            </a>
            <a
              class="text-green-700"
              href="https://drive.google.com/file/d/1rbCApN_f4aQHsKjcAqRh1VNI2eo6oIi8/view?usp=sharing"
              target="_blank"
            >
              Project Calendar
            </a>
          </DeliverableListItem>
          <DeliverableListItem title="Milestone 2">
            <a
              class="text-green-700 mb-1"
              href="https://drive.google.com/file/d/1H00KauyTm29SkFJCqws-yJVznBiG48td/view"
              target="_blank"
            >
              Presentation 2
            </a>
          </DeliverableListItem>
          <DeliverableListItem title="Milestone 3">
            <a
              class="text-green-700 mb-1"
              href="https://docs.google.com/document/d/16UFmkMJ-i8q-4or0ycxHj_vfLrHwbZjD6G64MFQghWI/edit?usp=sharing"
              target="_blank"
            >
              Prototype Report
            </a>
          </DeliverableListItem>
          <DeliverableListItem title="Milestone 4">
            <a
              class="text-green-700 mb-1"
              href="https://drive.google.com/file/d/1sObV4ARjRxNqO3Omm_jdqCCd7QcIDRdT/view?usp=sharing"
              target="_blank"
            >
              Final Report
            </a>
          </DeliverableListItem>
        </div>
      </div>
    </div>
  </div>
</div>
