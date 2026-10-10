<style>
  /* ═══════════════════════════════════════════
     ANIMATIONS  (rendered on websites / local previews)
     GitHub strips <style>, but the GIFs & animated
     SVGs below still animate everywhere.
     ═══════════════════════════════════════════ */

  @keyframes gradientShift {
    0%   { background-position: 0% 50%; }
    50%  { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }

  @keyframes floaty {
    0%, 100% { transform: translateY(0px); }
    50%      { transform: translateY(-14px); }
  }

  @keyframes pulseGlow {
    0%, 100% { box-shadow: 0 0 0 0 rgba(0, 247, 255, 0.75); }
    70%      { box-shadow: 0 0 0 14px rgba(0, 247, 255, 0); }
  }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(28px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  @keyframes slideInLeft {
    from { opacity: 0; transform: translateX(-40px); }
    to   { opacity: 1; transform: translateX(0); }
  }

  @keyframes borderRun {
    0%   { background-position: 0% 50%; }
    100% { background-position: 200% 50%; }
  }

  /* Animated gradient headline text */
  .grad-text {
    background: linear-gradient(90deg, #00F7FF, #0A66C2, #6A00FF, #00F7FF);
    background-size: 300% 300%;
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: gradientShift 6s ease infinite;
    font-weight: 800;
  }

  .float      { animation: floaty 5s ease-in-out infinite; }
  .pulse      { animation: pulseGlow 2.2s infinite; border-radius: 6px; }
  .fade-up    { animation: fadeUp 0.9s ease both; }
  .slide-left { animation: slideInLeft 0.9s ease both; }

  .d1 { animation-delay: 0.15s; }
  .d2 { animation-delay: 0.30s; }
  .d3 { animation-delay: 0.45s; }
  .d4 { animation-delay: 0.60s; }

  /* Hover lift + neon glow on cards, badges, images */
  .lift {
    transition: transform .35s cubic-bezier(.2,.8,.2,1),
                box-shadow .35s ease,
                filter .35s ease;
  }
  .lift:hover {
    transform: translateY(-8px) scale(1.03);
    box-shadow: 0 12px 40px rgba(0, 247, 255, .45),
                0 0 0 1px rgba(0, 247, 255, .35);
    filter: brightness(1.12);
  }

  /* Animated running border for the "Open to Work" badge */
  .border-run {
    background: linear-gradient(90deg, #00F7FF, #0A66C2, #6A00FF, #00F7FF);
    background-size: 200% 200%;
    animation: borderRun 3s linear infinite;
    padding: 3px;
    border-radius: 8px;
    display: inline-block;
  }
</style>

<!-- ══════════════════════════════════════════════════════
     ANIMATED WAVE HEADER
     ══════════════════════════════════════════════════════ -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00F7FF,50:0A66C2,100:6A00FF&height=210&section=header&text=Rajesh%20R&fontSize=72&fontColor=ffffff&animation=fadeIn&fontAlignY=34&desc=Java%20Backend%20Engineer%20%E2%80%A2%20Spring%20Boot%20%E2%80%A2%20Microservices&descAlignY=56&descSize=20"/>

<!-- Animated typing headline -->
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00F7FF&center=true&vCenter=true&width=750&lines=Hi+%F0%9F%91%8B+I'm+Rajesh+R;Java+Backend+Engineer;Spring+Boot+%7C+Microservices+%7C+REST+APIs;Designing+Scalable+Backend+Systems;Clean+Code+%7C+Secure+APIs+%7C+Real+Impact"/>

<br/>

<!-- Animated divider -->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900"/>

<br/>

<p>
<a href="mailto:rayudurajesh2001@gmail.com">
<img class="lift" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://linkedin.com/in/rajesh-r-9920r8843">
<img class="lift" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/RAJESH">
<img class="lift" src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white"/>
</a>
</p>

<p>
<img src="https://komarev.com/ghpvc/?username=RAJESH&color=00F7FF&style=for-the-badge&label=PROFILE+VIEWS"/>
<img src="https://img.shields.io/github/followers/RAJESH?label=FOLLOWERS&style=for-the-badge&color=00F7FF&logo=github"/>
<span class="border-run"><img src="https://img.shields.io/badge/OPEN%20TO%20WORK-Backend%20Engineering-0A66C2?style=for-the-badge&logo=checkmarx&logoColor=white"/></span>
</p>

</div>

<br/>

<!-- ══════════════════════════════════════════════════════
     ABOUT ME  +  FLOATING DEV GIF
     ══════════════════════════════════════════════════════ -->
<img class="float" align="right" width="340" src="https://raw.githubusercontent.com/rajathkumarmp/rajathkumarmp/master/assets/developer.gif"/>

## <span class="grad-text">👨‍💻 About Me</span>

```java
public class RajeshR implements BackendEngineer {

    private final String   role    = "Java Backend Developer";
    private final String   focus   = "Secure, scalable, high-performance systems";
    private final String[] values  = { "Clean Architecture",
                                       "Solid Data Modeling",
                                       "Production-Grade Code" };

    @Override
    public String mission() {
        return "Turn complex ideas into reliable software that scales.";
    }
}
