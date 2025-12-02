public class ProjectPlan2 {
    public static void main(String[] args) {
        System.out.println("Introduction: Welcome to the project workspace! "
            + "This page outlines the key elements of our project setup, including team roles, milestones, and the overall plan.\n");

        String[] roles = {
            "Project Manager: Leads planning, coordination, and communication",
            "Developer: Builds and implements core features",
            "Tester: Validates functionality and ensures quality",
            "Designer: Crafts UI/UX and visual assets"
        };

        String[] milestones = {
            "Kickoff: Team alignment and project charter",
            "Requirements Finalized: Functional and technical specifications",
            "Design Completion: Wireframes and mockups",
            "Development Phase: MVP or working prototype",
            "Testing & QA: Bug reports and validation",
            "Final Delivery: Fully functional product"
        };

        String[] summary = {
            "Objectives: Deliver a scalable, user-friendly solution",
            "Scope: Define included features and exclusions",
            "Timeline: Start to finish with key phases",
            "Resources: Team members, tools (Jira, Confluence, Figma), and budget"
        };

        printSection("Team Roles", roles);
        printSection("Milestones & Deliverables", milestones);
        printSection("Project Plan Summary", summary);
    }

    private static void printSection(String title, String[] items) {
        System.out.println(title);
        for (String item : items) {
            System.out.println(item);
        }
        System.out.println();
    }
}
