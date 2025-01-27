---
title: NRAU-Baltic
titleTemplate: false
---

<script setup lang="ts">
  import CountdownTimer from '@/components/CountdownTimer.vue'
  import { computed } from 'vue';

  const contestDate = new Date('2024-01-14T06:30:00Z')
  const now = new Date()

  const hasContestStarted = computed(() => now.getTime() > contestDate.getTime())
</script>

# NRAU-Baltic contest

<ClientOnly>
  <template v-if="!hasContestStarted">
    <h3>Contest starts in <CountdownTimer :date="contestDate" /></h3>
  </template>
</ClientOnly>

Welcome to the NRAU-Baltic contest 2024 on the 14th of January.

This year's contest host is [SSA](https://www.ssa.se/) (Sweden). Log upload and results can be found on the website https://<span>logs.nraubaltic.eu/</span>.

<a class="text-4xl font-bold" href="https://logs.nraubaltic.eu/submit/65947b7f2f903b1b56c43a15">SUBMIT YOUR LOG HERE >></a>

Supported contesting software that include the most recent NRAU-Baltic contest rule updates:

* **DXLog.net**: version 2.5.54 ([full download](https://dxlog.net/sw/files/DXLog.net-2.5.54.msi))

* **N1MM Logger+**: update 1.0.10151 ([update download](https://n1mmwp.hamdocs.com/mmfile/get/file/N1MM-Logger-Update-1.0.10151.exe))

_73, Ingo SM5AJV SSA HF Contest Manager_

---

The following NRAU-Baltic contests are hosted by:

- 2025 Sunday 12.1 2025 NRRL - Norway
- 2026 Sunday 11.1.2026 EDR - Denmark
- 2027 Sunday 10.1.2027 ERAU - Estonia
- 2028 Sunday 9.1.2028 LRAL - Latvia
- 2029 Sunday 14.1.2029 LRMD - Lithuania
- 2030 Sunday 13.1.2030 SRAL - Finland
- 2031 Sunday 12.1.2031 SSA - Sweden
