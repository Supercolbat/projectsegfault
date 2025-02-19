<script lang="ts">
	import type { PageData } from "./$types";
	import PMargin from "$lib/PMargin.svelte";

	export let data: PageData;
</script>

<h1>{data.title}</h1>

<h2>We don't collect more information than we need to.</h2>

<PMargin
	>We have disabled request logging. This is because it is extremely
	identifiable. This means that, for example, what website you visited and
	what path you visited (like https://libreddit.projectsegfau.lt/r/cats), your
	IP address, your User-Agent will not be logged by us!</PMargin
>

<PMargin
	>Some of our services have things like databases and things, for example <a
		href="https://chat.projectsegfau.lt">Matrix</a
	>, but that should be pretty obvious the moment you make an account on
	there. They may collect some things, however we barely even access those
	databases so you should be fine.</PMargin
>

<PMargin
	><a href="https://chat.projectsegfau.lt">Matrix</a> logs IPs, there is nothing
	we can do to prevent that. We will only check IP addresses whenever there is
	serious abuse coming from someone's Matrix account, so we can ban their IP from
	using Project Segfault services. This includes, but is not limited to ban evading
	and harassment of communities and people.</PMargin
>

<PMargin
	>If you want the data we've collected on you to be sent, please contact us
	on Matrix in <a href="https://matrix.to/#/#gdpr:projectsegfau.lt"
		>this room</a
	>, or e-mail us at
	<a href="mailto:contact@projectsegfau.lt">contact@projectsegfau.lt</a>. You
	don't need an account on our Matrix instance in order to chat there, you can
	choose from a bunch of public instances or make your own.</PMargin
>

<h2>For our website and blog</h2>

<PMargin
	>We have Plausible analytics installed on our website (the one you are on
	right now!), and our <a href="https://blog.projectsegfau.lt">blog</a>, which
	means we can just easily see what part of our site you're on, what country
	you are from, what platform you are from, potentially a referrer and all
	those get clumped up together.</PMargin
>

<PMargin class="italic"
	>Plausible Analytics is completely anonymous. We can't exactly figure out
	who you are through Plausible. It is also GDPR compliant.</PMargin
>

<PMargin
	>We use analytics in order to see how many visitors we get every day, what
	pages get visited the most, what countries visit our website the most etc.
	uBlock and other privacy extensions block Plausible by default.</PMargin
>

<PMargin
	>If you would like to see our website's statistics, <a
		href="https://analytics.projectsegfau.lt/projectsegfau.lt"
		>look no further</a
	>.</PMargin
>

<h2>
	We don't give any of the data we collect to anyone outside of Project
	Segfault.
</h2>

<PMargin
	>What we just described above won't be sold or given to anyone outside of
	Project Segfault, except for anonymous analytics like the website. Some data
	could be given to law enforcement if they have a warrant.</PMargin
>

<PMargin
	>There is no reason for anyone outside of Project Segfault to see your data.
	In fact, Project Segfault really has no reason to see your data, unless
	there's something to suspect.</PMargin
>

<h2>Data may be cleared at any point upon request, but...</h2>

<PMargin
	>There are times when we are unable to delete "your" data because we
	sometimes we do not have a concept of "you". If you don't create an account
	on the services you use, we have no way to know what data is tied to "you"
	as most logs are anonymized.</PMargin
>

<PMargin
	>Often times you can clear your own data simply by deleting your account.</PMargin
>

<PMargin
	>As we said, you can request any GDPR/Privacy things in <a
		href="https://matrix.to/#/#gdpr:projectsegfau.lt">this Matrix room</a
	>. But, if there's any ongoing investigations and a law enforcement agency
	contacts us, we will comply. But, we will only do it if we can verify it's
	official and they have a warrant.</PMargin
>

<span class="italic">Last updated 09.08.2022 16:57 UTC+1</span>
