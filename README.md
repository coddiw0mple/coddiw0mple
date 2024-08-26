<!---
coddiw0mple/coddiw0mple is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
```java
public class Divith extends About {
    private static final String NAME = "Divith Phogat";
    private static final String LOCATION = "Bengaluru, India";
    private static final String EMAIL = "divithphogat@gmail.com";

    public static String getWorkplace() {
        String workplace = "Oracle India";
        return workplace;
    }

    public static Map<String, String> getProjects() {
        Map<String, String> projects = new HashMap<>();
        projects.put("TinyDerma", "An android app to classify skin lesions using Computer Vision (Flutter, Pytorch, Firebase, Python, Dart)");
        projects.put("GeneAI", "A web extension to aid users in writing better documents faster using GPT (Javascript, ChatGPT, OpenAI API)");
        return projects;
    }

    public static Map<String, String[]> getSkills() {
        Map<String, String[]> skills = new HashMap<>();
        skills.put("Programming Languages", new String[]{"Java", "Python", "HTML/CSS", "Dart", "C++", "Rust"});
        skills.put("Databases", new String[]{"MongoDB", "PostgreSQL", "Firestore", "Redis"});
        skills.put("Frameworks/Libraries", new String[]{"TensorFlow", "Flutter", "PyTorch", "React", "Node.js", "Next.js"});
        skills.put("Developer Tools", new String[]{"Git", "Firebase", "Supabase", "AWS", "Google Cloud Platform"});
        return skills;
    }

    public static String getFutureGoal() {
        return "To become a world-renowned AI expert and create SkyNet";
    }

    public static void saveTech() {
        // TODO: Figure out how to save the world with tech
        throw new NotYetImplementedException();
    }

    public static void main(String[] args) {
        System.out.println("Divith Phogat, at your service!");
        saveTech();
    }
}
```
