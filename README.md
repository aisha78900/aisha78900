# ================================================
#            🌟 AYESHA – THE BOT MAKER 🌟
#       SaaS Engineer | AI Explorer | Pythonista
# ================================================

class AyeshaBot:
    def __init__(self):
        self.name = "Ayesha"
        self.skills = ["🤖 Telegram Bots", "🌐 SaaS Tools", "🧠 AI Projects"]
        self.tools = ["Python", "FastAPI", "Next.js", "OpenAI", "Langchain"]
        self.status = "Building smart systems that work while I sleep 😴"

    def portfolio(self):
        return f"""
        🔧 CURRENTLY WORKING ON:
        - AI Automation Tools
        - Bot-Based SaaS Platforms
        - Smart Client Solutions
        
        📬 CONNECT WITH ME:
        GitHub: github.com/AyeshaOwais
        LinkedIn: linkedin.com/in/ayesha-dev
        """

    def vibe(self):
        return "✨ Turning caffeine into intelligent code & cute bugs 🐞"

ayesha = AyeshaBot()

if __name__ == "__main__":
    print("🚀 Meet", ayesha.name)
    print("🛠️ Skills:", ", ".join(ayesha.skills))
    print("💻 Tools:", ", ".join(ayesha.tools))
    print(ayesha.portfolio())
    print(ayesha.vibe())
