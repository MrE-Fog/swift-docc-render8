<!--
  This source file is part of the Swift.org open source project

  Copyright (c) 2022 Apple Inc. and the Swift project authors
  Licensed under Apache License v2.0 with Runtime Library Exception

  See https://swift.org/LICENSE.txt for license information
  See https://swift.org/CONTRIBUTORS.txt for Swift project authors
-->

<template>
  <SVGIcon
    class="link-icon"
    viewBox="0 0 20 20"
  >
    <path d="M19.34,4.88L15.12,.66c-.87-.87-2.3-.87-3.17,0l-3.55,3.56-1.38,1.38-1.4,1.4c-.47,.47-.68,1.09-.64,1.7,.02,.29,.09,.58,.21,.84,.11,.23,.24,.44,.43,.63l4.22,4.22h0l.53-.53,.53-.53h0l-4.22-4.22c-.29-.29-.29-.77,0-1.06l1.4-1.4,.91-.91,.58-.58,.55-.55,2.9-2.9c.29-.29,.77-.29,1.06,0l4.22,4.22c.29,.29,.29,.77,0,1.06l-2.9,2.9c.14,.24,.24,.49,.31,.75,.08,.32,.11,.64,.09,.96l3.55-3.55c.87-.87,.87-2.3,0-3.17Z"/>
    <path d="M14.41,9.82s0,0,0,0l-4.22-4.22h0l-.53,.53-.53,.53h0l4.22,4.22c.29,.29,.29,.77,0,1.06l-1.4,1.4-.91,.91-.58,.58-.55,.55h0l-2.9,2.9c-.29,.29-.77,.29-1.06,0L1.73,14.04c-.29-.29-.29-.77,0-1.06l2.9-2.9c-.14-.24-.24-.49-.31-.75-.08-.32-.11-.64-.09-.97L.68,11.93c-.87,.87-.87,2.3,0,3.17l4.22,4.22c.87,.87,2.3,.87,3.17,0l3.55-3.55,1.38-1.38,1.4-1.4c.47-.47,.68-1.09,.64-1.7-.02-.29-.09-.58-.21-.84-.11-.22-.24-.44-.43-.62Z"/>
  </SVGIcon>
</template>

<script>
import SVGIcon from 'docc-render/components/SVGIcon.vue';

export default {
  name: 'LinkIcon',
  components: { SVGIcon },
};
</script>
