![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=jesusanachur.jesusanachur)

<div align="center">
  
# ¡Hola, soy Jesús David! 👋💻

Soy un apasionado desarrollador full-stack con amor por el código limpio y soluciones innovadoras. ¡Aprendizaje continuo es mi lema!

## 🌱 Mi Mundo Tech

<table>
  <tr>
    <td width="50%">
      <h3>🚀 Actualmente</h3>
      <ul>
        <li>Aprendiendo <strong>Go</strong> y <strong>Django</strong></li>
        <li>Construyendo una app para aprender idiomas</li>
        <li>Colaborando en proyectos <strong>open-source</strong></li>
      </ul>
    </td>
    <td width="50%">
      <h3>📬 Contáctame</h3>
      <ul>
        <li>📧 <a href="mailto:anachurycastro2001@gmail.com">anachurycastro2001@gmail.com</a></li>
        <li>📞 +57 311 244 5775</li>
        <li>💼 <a href="https://www.linkedin.com/in/jes%C3%BAs-david-anachury-castro-762776273/">LinkedIn</a></li>
      </ul>
    </td>
  </tr>
</table>

## 🛠️ Stack Tecnológico

<div align="center">

![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-%23CC2927.svg?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

</div>


[![GitHub Streak](https://streak-stats.demolab.com?user=jesusanachur&theme=radical&border_radius=5&mode=weekly)](https://git.io/streak-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=jesusanachur&layout=compact&theme=radical&hide_border=true)](https://github.com/anuraghazra/github-readme-stats)

</div>

## 🌟 Proyectos Destacados

<div align="center">

| Proyecto       | Descripción          | Tech Stack  |
|----------------|----------------------|-------------|
| [App Idiomas]() | Aprendizaje de idiomas | Django, MongoDB |
| [SQL Explorer]() | Herramienta SQL visual | Java, SQL Server |

</div>

import time
import random

class DeveloperAdventure:
    def __init__(self):
        self.skills_unlocked = 0
        self.projects_completed = 0
        self.recruiter_impression = 0
        
    def type_effect(self, text, delay=0.03):
        for char in text:
            print(char, end='', flush=True)
            time.sleep(delay)
        print()
    
    def show_title(self):
        print("🎮" * 30)
        self.type_effect("🌟 AVENTURA DEL DESARROLLADOR JUNIOR 🌟")
        self.type_effect("¿Podrás descubrir al próximo talento tech?")
        print("🎮" * 30)
        time.sleep(1)
    
    def start_adventure(self):
        self.show_title()
        
        self.type_effect("\n📧 Has recibido un CV misterioso...")
        time.sleep(1)
        self.type_effect("💡 Nombre: Jesús David Anachury Castro")
        self.type_effect("🎯 Objetivo: Programador Backend Junior")
        time.sleep(2)
        
        input("\n🎲 Presiona ENTER para explorar sus habilidades...")
        self.explore_skills()
    
    def explore_skills(self):
        print("\n" + "🛠️" * 20)
        self.type_effect("NIVEL 1: DESCUBRE LAS HABILIDADES TÉCNICAS")
        print("🛠️" * 20)
        
        skills = [
            "🐍 Python - Nivel: Intermedio",
            "🌐 Django - Nivel: Intermedio", 
            "🗄️ PostgreSQL - Nivel: Básico-Intermedio",
            "📱 HTML/CSS/JS - Nivel: Intermedio",
            "⚡ Git/GitHub - Nivel: Intermedio"
        ]
        
        for i, skill in enumerate(skills, 1):
            self.type_effect(f"{i}. {skill}")
            time.sleep(0.5)
        
        choice = input("\n🔍 ¿Qué habilidad quieres probar? (1-5): ")
        
        if choice in ["1", "2", "3"]:
            self.type_effect("✅ ¡Habilidad backend detectada! +10 puntos")
            self.skills_unlocked += 10
            self.recruiter_impression += 10
        else:
            self.type_effect("💡 Buen conocimiento full-stack +5 puntos")
            self.skills_unlocked += 5
            self.recruiter_impression += 5
        
        input("\n🎲 Presiona ENTER para ver sus proyectos...")
        self.explore_projects()
    
    def explore_projects(self):
        print("\n" + "🚀" * 20)
        self.type_effect("NIVEL 2: EXPLORA LOS PROYECTOS")
        print("🚀" * 20)
        
        projects = [
            "📘 Comunidad Educativa (Django + JavaScript)",
            "🎮 Videojuego Sokoban (Python + Pygame)", 
            "🗓️ Sistema de Citas (CRUD completo)"
        ]
        
        for i, project in enumerate(projects, 1):
            self.type_effect(f"{i}. {project}")
            time.sleep(0.8)
        
        self.type_effect("\n🎯 Todos los proyectos incluyen:")
        self.type_effect("   • Código limpio y documentado")
        self.type_effect("   • Soluciones creativas")
        self.type_effect("   • Aprendizaje continuo")
        
        self.projects_completed = 3
        self.recruiter_impression += 15
        
        input("\n🎲 Presiona ENTER para el desafío final...")
        self.final_challenge()
    
    def final_challenge(self):
        print("\n" + "⚡" * 20)
        self.type_effect("DESAFÍO FINAL: ¿CONTRATAR O NO CONTRATAR?")
        print("⚡" * 20)
        
        self.type_effect("\n🤔 El candidato muestra:")
        self.type_effect("   ✅ Pasión por programar")
        self.type_effect("   ✅ Proyectos reales implementados") 
        self.type_effect("   ✅ Aprendizaje autodidacta")
        self.type_effect("   ✅ Visión de crecimiento")
        
        time.sleep(2)
        
        self.type_effect(f"\n📊 PUNTUACIÓN OBTENIDA:")
        self.type_effect(f"   🛠️  Habilidades: {self.skills_unlocked}/10")
        self.type_effect(f"   🚀 Proyectos: {self.projects_completed}/3")
        self.type_effect(f"   💼 Impresión: {self.recruiter_impression}/30")
        
        total_score = self.skills_unlocked + (self.projects_completed * 5) + self.recruiter_impression
        
        time.sleep(1)
        
        if total_score >= 35:
            self.type_effect(f"\n🎉 PUNTUACIÓN TOTAL: {total_score}/50")
            self.type_effect("🏆 ¡FELICIDADES! Has encontrado un talento oculto")
            self.type_effect("📞 Contacta a: anachurycastro2001@gmail.com")
            self.type_effect("💻 Portafolio: github.com/jesusanachur")
            self.type_effect("🌟 ¡El viaje apenas comienza!")
        else:
            self.type_effect("\n💡 Tal vez necesites revisar más proyectos...")
            self.type_effect("🔄 Reiniciando aventura...")
            time.sleep(2)
            self.__init__()
            self.start_adventure()
    
    def play(self):
        self.start_adventure()

# ¡Iniciar el juego!
if __name__ == "__main__":
    game = DeveloperAdventure()
    game.play()
