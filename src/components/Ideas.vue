import { db } from './db'

export default {
  data() {
    return {
      ideas: [],
    }
  },

  firestore: {
    ideas: db.collection('ideas'),
  },
}
