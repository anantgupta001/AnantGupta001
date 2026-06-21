<div align="center">

```
┌─ AnantGupta.java ───────────────────────────────────────────────┐
```

</div>

```java
package com.anantgupta;

/**
 * Software Engineer Intern @ Growspace
 * B.Tech, Computer Science — VIT Vellore, Class of 2026
 * Based in Jaipur, Rajasthan, India
 */
public class AnantGupta {

    private static final String EMAIL    = "anantagarwal4946@gmail.com";
    private static final String GITHUB   = "github.com/anantgupta001";
    private static final String LINKEDIN = "linkedin.com/in/anantgupta7628";
    private static final String LEETCODE = "leetcode.com/anantgupta001";

    private final List<String> languages  = List.of("Java", "SQL", "JavaScript", "TypeScript");
    private final List<String> frameworks = List.of("Spring Boot", "Angular", "React", "Next.js", "Flutter", "Node.js");
    private final List<String> infra      = List.of("Kafka", "Redis", "PostgreSQL", "MySQL", "MongoDB", "GCP", "AWS", "Firebase");
    private final List<String> tooling    = List.of("JUnit", "Mockito", "SonarQube", "Git");

    /**
     * Current role @ Growspace — Jan 2026 to Present.
     * Backend systems for a telecom SIM management platform
     * operating at a scale of tens of millions of SIMs.
     */
    public void currentRole() {
        buildAuthSystem("JWT", "Redis");
        // login, logout, token refresh, password reset,
        // cross-device session invalidation, concurrent session limits

        designOrgHierarchy("Seed", "Root", "Child", "Orphan");
        // multi-tenant hierarchy w/ org-level feature provisioning
        // and fine-grained RBAC

        optimizeRuleEngine("Kafka", "Redis", "Cron");
        // event-driven rule engine, scalable evaluation across
        // tens of millions of SIMs

        executeFaultTolerant("email", "sms", "reporting", "inventory");
        // Kafka fan-out patterns + idempotent event handlers

        maintainCoverage(80); // JUnit + Mockito, enforced via SonarQube
    }

    public static void main(String[] args) {
        AnantGupta me = new AnantGupta();
        me.currentRole();

        System.out.println("Open to interesting backend & systems work.");
    }
}
```

<div align="center">

```
└───────────────────────────────────────────────────────────────┘
```

</div>

<br>

<div align="center">

```
┌─ open-source.log ────────────────────────────────────────────────┐
```

</div>

```diff
$ git log --oneline --stat --author="anantgupta001"

dbeaver/dbeaver  (Java, SWT, Eclipse RCP, Maven)
+ PR #41337  [APPROVED]  Theme-aware compiler log colors
             Replaced hardcoded SWT colors with configurable theme
             definitions, improving dark-theme accessibility.

+ PR #41349            Fixed theme-refresh regressions
             Object editor panels and result grids retained stale
             colors after Dark <-> Light theme switches. Resolved.

lichess-org/lila  (Scala, TypeScript, Play Framework)
+ PR #20715            Fixed UI theming inconsistencies
             Reusable adaptive hover styling for custom image
             backgrounds.

anantgupta001/ffcs-on-the-go  (JavaScript, HTML)
+ PR #247    [MERGED]   Added VIT-AP campus support
             Integrated campus-specific course & timetable data.
```

<div align="center">

```
└────────────────────────────────────────────────────────────────┘
```

</div>

<br>

<div align="center">

```
┌─ projects.json ──────────────────────────────────────────────────┐
```

</div>

```json
{
  "projects": [
    {
      "name": "VITor — Faculty Rating Platform",
      "stack": ["Next.js", "React", "Firebase", "Tailwind CSS"],
      "live": "vitor-facultyranker.vercel.app",
      "description": "Full-stack anonymous faculty review platform covering 1,500+ faculty and 500+ reviews across all VIT campuses.",
      "highlights": [
        "Firebase authentication",
        "campus-based access control",
        "rate limiting",
        "paginated review APIs"
      ]
    },
    {
      "name": "CraVIT — Food Ordering Platform",
      "stack": ["Flutter", "Firebase", "Razorpay"],
      "repo": "github.com/anantgupta001/cravit",
      "description": "Modular monorepo with separate student and seller apps.",
      "highlights": [
        "Firebase Auth",
        "Razorpay payment integration",
        "real-time push notifications via FCM"
      ]
    },
    {
      "name": "FFCS on the Go",
      "stack": ["JavaScript", "HTML"],
      "description": "Open-source course enrollment tool with a large active user base across VIT campuses."
    }
  ]
}
```

<div align="center">

```
└────────────────────────────────────────────────────────────────┘
```

</div>

<br>

<div align="center">

```
┌─ ~/anantgupta — zsh ─────────────────────────────────────────────┐
```

</div>

```bash
$ whoami --education

  Vellore Institute of Technology
  B.Tech, Computer Science | 2022 – 2026 | CGPA: 8.39

$ whoami --stats

  LeetCode      600+ problems solved · 1600+ contest rating

$ contact --me

  Email      anantagarwal4946@gmail.com
  LinkedIn   linkedin.com/in/anantgupta7628
  GitHub     github.com/anantgupta001
  LeetCode   leetcode.com/anantgupta001

$ _
```

<div align="center">

```
└────────────────────────────────────────────────────────────────┘
```

</div>
