# Chef Claude 🍳🤖

An intelligent AI-powered recipe generator that helps you create delicious meals based on the ingredients you have on hand. Powered by Anthropic's Claude AI, Chef Claude transforms your available ingredients into creative, personalized recipes.

## ✨ Features

- **Ingredient-Based Recipe Generation**: Simply input your available ingredients and get customized recipes
- **AI-Powered Suggestions**: Leverages advanced AI to create unique and practical recipes
- **Smart Recommendations**: Considers cooking methods, dietary preferences, and ingredient combinations
- **User-Friendly Interface**: Clean, intuitive design for seamless recipe discovery
- **Flexible Input**: Works with any combination of ingredients you have available
- **Detailed Instructions**: Provides step-by-step cooking instructions and ingredient measurements

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager
- Anthropic API key (for Claude AI integration)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Bhuvaneshreddy12/chef-claude.git
cd chef-claude
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Create a `.env` file in the root directory and add your environment variables:
```env
REACT_APP_ANTHROPIC_API_KEY=your_anthropic_api_key_here
```

4. Start the development server:
```bash
npm start
# or
yarn start
```

5. Open your browser and navigate to `http://localhost:3000`

## 🛠️ Usage

1. **Enter Your Ingredients**: Add the ingredients you have available in your kitchen
2. **Specify Preferences** (optional): Include any dietary restrictions, cooking time preferences, or cuisine types
3. **Generate Recipe**: Click the generate button to let Chef Claude create a personalized recipe
4. **Follow Instructions**: Get detailed step-by-step cooking instructions with measurements
5. **Enjoy Cooking**: Create delicious meals with confidence!

### Example

Input ingredients: "chicken breast, broccoli, garlic, olive oil, lemon"
Output: A complete recipe with preparation steps, cooking instructions, and serving suggestions.

## 🏗️ Project Structure

```
chef-claude/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── IngredientInput.js
│   │   ├── RecipeDisplay.js
│   │   └── Header.js
│   ├── services/
│   │   └── anthropicAPI.js
│   ├── styles/
│   │   └── App.css
│   ├── App.js
│   └── index.js
├── package.json
├── .env.example
└── README.md
```

## 🔧 Technologies Used

- **Frontend**: React.js, HTML5, CSS3
- **AI Integration**: Anthropic Claude API
- **HTTP Client**: Axios or Fetch API
- **Styling**: CSS3 with modern design principles
- **State Management**: React Hooks

## 🌟 Key Components

### IngredientInput Component
Handles user input for ingredients and preferences with intuitive form controls.

### RecipeDisplay Component
Renders the generated recipes with proper formatting and styling for optimal readability.

### AnthropicAPI Service
Manages API calls to Claude AI, handling request formatting and response processing.

## 🚀 Deployment

### Deploy to Vercel
```bash
npm install -g vercel
vercel --prod
```

### Deploy to Netlify
1. Build the project: `npm run build`
2. Drag and drop the `build` folder to Netlify
3. Configure environment variables in Netlify settings

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Anthropic](https://www.anthropic.com/) for providing the Claude AI API
- The React community for excellent documentation and resources
- Contributors and testers who helped improve this application

## 📞 Contact

**Bhuvanesh Reddy**
- GitHub: https://github.com/tejavardhan49
- Project Link: https://github.com/tejavardhan49/CHEF-CLAUDE

## 🔮 Future Enhancements

- [ ] Save favorite recipes
- [ ] Nutrition information display
- [ ] Shopping list generation
- [ ] Recipe sharing functionality
- [ ] Multi-language support
- [ ] Voice input for ingredients
- [ ] Recipe rating and reviews
- [ ] Meal planning integration


