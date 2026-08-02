# Abdul Wali Dal

<a href="https://github.com/abdulwalidal">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&pause=1200&color=3FB950&vCenter=true&width=560&height=30&lines=%24+curl+-s+api.abdulwalidal.dev%2Fstatus;%3E+200+OK+%E2%80%94+backend+developer+online;%3E+running+on+Java+%2B+Spring+Boot" alt="status" />
</a>

Backend developer, Software Engineering '27. I don't have a public API — but if I did, it might look like this:

---

```java
@RestController
@RequestMapping("/abdul-wali-dal")
public class Developer {

    private final String role = "Backend Developer";

    // dependencies wired across 12+ Spring Boot services
    @Autowired private Java           language;      // primary
    @Autowired private SpringBoot     framework;     // Web · MVC · Data JPA
    @Autowired private SpringSecurity auth;          // secured with JWT
    @Autowired private Database       data;          // MongoDB · MySQL · H2
    @Autowired private OpenAPI        docs;          // springdoc / Swagger
    @Autowired private SpringAI       experiments;   // OpenAI integration

    @GetMapping("/now")
    public String currentlyBuilding() {
        return "REST APIs, auth systems, and products that actually ship.";
    }

    @GetMapping("/philosophy")
    public String why() {
        return "Understand *why* it works — not just how.";
    }
}
```

## ▍Featured &nbsp;·&nbsp; `GET /projects/wird`

> **`200 OK`** &nbsp;·&nbsp; live in production &nbsp;·&nbsp; deployed to Google Play

```json
{
  "app":      "Wird — Islamic Habits & Dhikr",
  "about":    "Build daily Islamic habits and track your dhikr.",
  "status":   "LIVE",
  "platform": "Google Play"
}
```

<a href="https://play.google.com/store/apps/details?id=io.wird.app">
  <img src="https://img.shields.io/badge/Get_it_on-Google_Play-3FB950?style=for-the-badge&logo=google-play&logoColor=white" alt="Get it on Google Play" height="38" />
</a>

---

### `GET` /connect

| Route | Response |
|:--|:--|
| **`/linkedin`** | [linkedin.com/in/abdul-wali-dal](https://www.linkedin.com/in/abdul-wali-dal-9653b6288/) |
| **`/email`** | [abdulwalidal@gmail.com](mailto:abdulwalidal@gmail.com) |
| **`/github`** | [@abdulwalidal](https://github.com/abdulwalidal) |
