# Random Joke Generator 😂

A fun and interactive web application that fetches random jokes from an external API. Get a laugh anytime!

## Features

- 🎲 **Random Jokes**: Fetch random jokes with a single click
- 🎯 **Joke Types**: Filter jokes by type (Any, Single, Two-part)
- 📋 **Copy Functionality**: Easily copy jokes to share with friends
- 🎨 **Beautiful UI**: Modern and responsive design
- 📊 **Joke Counter**: Track how many jokes you've fetched
- ⚡ **Error Handling**: Graceful error messages and loading states
- 📱 **Mobile Friendly**: Works perfectly on all devices

## How to Use

1. Open `index.html` in your web browser
2. Select your preferred joke type:
   - **Any**: Random jokes (single or two-part)
   - **Single**: Single-line jokes only
   - **Two-part**: Setup and punchline jokes
3. Click the "Get Joke" button to fetch a random joke
4. Click "Copy Joke" to copy the joke to your clipboard
5. Share and laugh! 😄

## API Used

This project uses the **Joke API** - a free, open-source API for random jokes.

- **API Endpoint**: `https://v2.jokeapi.dev/joke/Any`
- **Documentation**: https://jokeapi.dev/
- **No API Key Required**: The API is completely free to use

## Joke Types

### Single Jokes
Complete jokes in a single sentence.
```
"Why don't scientists trust atoms? Because they make up everything!"
```

### Two-Part Jokes
Jokes with a setup and punchline.
```
Setup: "Why did the scarecrow win an award?"
Delivery: "He was outstanding in his field!"
```

## Technologies Used

- **HTML5**: Structure and layout
- **CSS3**: Styling with gradients and animations
- **Vanilla JavaScript**: API calls and DOM manipulation
- **Fetch API**: Asynchronous HTTP requests

## Project Structure

```
random-joke-generator/
├── index.html   (Complete application)
└── README.md    (Documentation)
```

## Features Explained

### Dynamic Joke Fetching
- Fetches jokes asynchronously using the Fetch API
- Supports filtering by joke type
- Shows loading state while fetching

### Copy to Clipboard
- One-click joke copying for easy sharing
- Works with both single and two-part jokes

### Error Handling
- Displays user-friendly error messages
- Handles network failures gracefully
- Validates API responses

### Responsive Design
- Mobile-first approach
- Works on all screen sizes
- Touch-friendly buttons

## Future Enhancements

- [ ] Add joke search/filter by category
- [ ] Dark mode toggle
- [ ] Joke history/favorites
- [ ] Share to social media buttons
- [ ] Rating system for jokes
- [ ] Multiple language support
- [ ] Offline joke storage
- [ ] Joke of the day feature

## Keyboard Shortcuts

- **Enter**: Get a new joke (optional enhancement)
- **Ctrl/Cmd + C**: Copy joke after fetching

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Lightweight: Single HTML file
- Fast load time: No build process required
- Efficient API calls: Minimal data transfer
- Smooth animations: CSS-based transitions

## License

MIT License - Feel free to use and modify this project!

## Credits

- **Joke API**: https://jokeapi.dev/
- **Built with**: HTML5, CSS3, Vanilla JavaScript

---

**Ready to laugh?** Open `index.html` and start generating jokes! 😂
