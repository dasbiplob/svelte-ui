<script>
    import Counter from "../components/Counter.svelte";
    import Hello from '../components/Hello.svelte';
    import QuestionAndAnswer from '../components/QuestionAndAnswer.svelte';
    let qa = {
    question: "Can this work?",
    answer: "Yes it can!",
  };
</script>
  


<Hello />
<Counter />
<QuestionAndAnswer {...qa} />

<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
  