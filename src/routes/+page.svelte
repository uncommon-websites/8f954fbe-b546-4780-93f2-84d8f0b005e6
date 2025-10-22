<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons
	import IconMic from "~icons/lucide/mic";
	import IconZap from "~icons/lucide/zap";
	import IconNetwork from "~icons/lucide/network";
	import IconClock from "~icons/lucide/clock";
	import IconTarget from "~icons/lucide/target";
	import IconGraduationCap from "~icons/lucide/graduation-cap";
</script>

<Hero
	centered={false}
	title="AI teachers that adapt to your child in real-time"
	subtitle="Personalized one-on-one tutoring for elementary students, powered by proactive voice AI that interrupts, guides, and adjusts to fill learning gaps."
	imageSrc="/generated/image-an-elementary-aged-child-sitting-at-a-ti.webp"
/>
<LogoScroller
	label="Trusted by families learning alongside"
	logoUrls={[
		'https://cdn.brandfetch.io/khanacademy.org/w/400/h/400/logo',
		'https://cdn.brandfetch.io/outschool.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/duolingo.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/brainly.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Proactive AI tutoring"
	text="Orin Labs builds AI teachers that adapt in real-time to each student's learning pace, filling gaps that traditional tutoring can't reach. We serve families with elementary-aged children who need consistent one-on-one support without the $60+ hourly cost or scheduling challenges of private tutors. Our proactive voice technology interrupts, guides, and adjusts dynamically, delivering personalized education that scales to meet every child's unique needs."
/>

<Testimonials
	testimonials={[
		{
			name: "Maria Rodriguez",
			position: "Homeschooling parent",
			company: "San Diego, CA",
			quote:
				"We were spending over $240 a week on private tutors just to keep up with math. Acadia Learning costs a fraction of that and my daughter actually looks forward to her sessions. She's finally filling those gaps without the scheduling nightmare.",
			image: "/generated/image-professional-headshot-of-maria-rodriguez.webp"
		},
		{
			name: "David Chen",
			position: "Parent of two",
			company: "Austin, TX",
			quote:
				"I was skeptical that AI could adapt to my son's learning pace, but after the demo I was blown away. The tutor interrupts when he's stuck and adjusts the curriculum in real-time. It's like having a patient teacher available 24/7.",
			image: "/generated/image-professional-headshot-of-david-chen-asia.webp"
		},
		{
			name: "Amara Williams",
			position: "Homeschool co-op coordinator",
			company: "Charlotte, NC",
			quote:
				"Finding consistent one-on-one tutoring that doesn't break the bank was impossible until Acadia. The real-time voice interaction keeps my kids engaged, and I've seen their confidence soar in just three weeks. No more fighting over homework.",
			image: "/generated/image-professional-headshot-of-amara-williams-.webp"
		}
	]}
/>

<Features
	title="How Orin teaches differently"
	subtitle="Proactive AI technology that adapts to your child's unique learning style"
	features={[
		{
			title: "Real-time voice interaction",
			description:
				"Natural voice conversations that flow like talking to a real tutor, creating engaging learning experiences your child actually looks forward to.",
			icon: IconMic
		},
		{
			title: "Proactive teaching approach",
			description:
				"AI teachers that actively interrupt, redirect, and push learning forward instead of waiting for questions.",
			icon: IconZap
		},
		{
			title: "Adaptive knowledge graphs",
			description:
				"Dynamic curriculum that adjusts in real-time based on your child's responses, ensuring they never fall behind or get bored.",
			icon: IconNetwork
		},
		{
			title: "Always available tutoring",
			description:
				"One-on-one tutoring whenever your child needs it for a fraction of the cost of traditional private tutors.",
			icon: IconClock
		},
		{
			title: "Fills learning gaps",
			description:
				"Identifies and addresses specific knowledge gaps through continuous assessment and targeted practice.",
			icon: IconTarget
		},
		{
			title: "Elementary-focused curriculum",
			description:
				"Specifically designed for elementary students with age-appropriate content, pacing, and engagement strategies that make learning fun.",
			icon: IconGraduationCap
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Give your child the tutoring they deserve"
	subtitle="Without the $240 weekly price tag"
	description="Join families who've discovered affordable, always-available AI tutoring that actually adapts to their child's learning pace. See it work in a free demo session."
	imageSrc="/generated/image-a-cheerful-parent-and-young-elementary-s.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Book a free demo",
			variant: "primary"
		},
		{
			href: "/pricing",
			label: "View pricing",
			variant: "secondary"
		}
	]}
/>
