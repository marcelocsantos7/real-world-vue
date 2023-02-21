<template>
  <div class="events">
    <h1 class="mb-4">Events for Good</h1>
    <EventCard v-for="event in events" :key="event.id" :event="event" />
  </div>
</template >

<script>
import EventCard from '@/components/EventCard.vue'

export default {
  name: 'EventList',
  components: {
    EventCard,
  },
  data() {
    return {
      events: [
        {
          id: 5928101,
          category: 'animal welfare',
          title: 'Cat Adoption Day',
          description: 'Find your new feline friend',
          location: 'Meow Town',
          date: 'January 28, 2022',
          time: '12:00',
          petsAlowed: true,
          organizer: 'Kat Laydee',
        },
        {
          id: 5928101,
          category: 'animal welfare',
          title: 'Cat Adoption Day',
          description: 'Find your new feline friend',
          location: 'Meow Town',
          date: 'January 28, 2022',
          time: '12:00',
          petsAlowed: true,
          organizer: 'Kat Laydee',
        },
        {
          id: 5928101,
          category: 'animal welfare',
          title: 'Cat Adoption Day',
          description: 'Find your new feline friend',
          location: 'Meow Town',
          date: 'January 28, 2022',
          time: '12:00',
          petsAlowed: true,
          organizer: 'Kat Laydee',
        },
        {
          id: 5928101,
          category: 'animal welfare',
          title: 'Cat Adoption Day',
          description: 'Find your new feline friend',
          location: 'Meow Town',
          date: 'January 28, 2022',
          time: '12:00',
          petsAlowed: true,
          organizer: 'Kat Laydee',
        },
        {
          id: 5928101,
          category: 'animal welfare',
          title: 'Cat Adoption Day',
          description: 'Find your new feline friend',
          location: 'Meow Town',
          date: 'January 28, 2022',
          time: '12:00',
          petsAlowed: true,
          organizer: 'Kat Laydee',
        },
      ]
    }
  }
}
</script>

<style scoped>
.events {
  margin-top: 2rem;
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>