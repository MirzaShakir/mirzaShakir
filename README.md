<div align="center">
  <h1>Hi there, I'm Mirza Shakir Baig 👋</h1>
  <p><strong>Sr. FullStack Lead | Enterprise Web Architect | PHP & Modern Frontend Specialist</strong></p>

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mirzashakir-baig-35761255/)
  [![Email](https://img.shields.io/badge/Email-baigmirzashakir%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:baigmirzashakir@gmail.com)
  [![Location](https://img.shields.io/badge/Location-Pune%2C%20India-blue?style=flat&logo=googlemaps&logoColor=white)](#)
</div>

<br/>

```php
<?php

namespace MirzaShakir;

class About extends SeniorFullStackLead
{
    public function getCurrentWorkplace(): array
    {
        return [
            'company'   => 'Kynetec Data Services Pvt. Ltd.',
            'position'  => 'Sr. FullStack Lead',
            'startDate' => 'Feb 2024',
            'location'  => 'Pune, India',
        ];
    }

    public function getCareerTimeline(): array
    {
        return [
            'CraftedQ (YCSPL)' => [
                'position'  => 'Technical Lead',
                'period'    => 'Oct 2022 – Oct 2023',
            ],
            'Frequence Software' => [
                'position'  => 'Sr. FullStack Engineer',
                'period'    => 'Feb 2019 – Oct 2022',
            ],
            'DbXento Systems' => [
                'position'  => 'Principal Engineer',
                'period'    => 'Aug 2014 – Feb 2019',
            ],
            'The MIIINT Solutions' => [
                'position'  => 'Software Developer',
                'period'    => 'Jan 2013 – Aug 2014',
            ],
            'Galaxy Info Tech' => [
                'position'  => 'Software Developer',
                'period'    => 'Mar 2008 – Mar 2010',
            ],
        ];
    }

    public function getCoreExpertise(): array
    {
        return [
            'backend' => [
                'primary'  => [Php::class, Laravel::class, Slim::class, NodeJs::class, GraphQL::class],
                'emerging' => ['Python' => '1.5 yrs'],
            ],
            'frontend_and_mobile' => [
                'primary'  => [Angular::class, TypeScript::class, TailwindCss::class],
                'emerging' => ['ReactJs' => '2.5 yrs', 'ReactNative' => '1 yr'],
            ],
            'database' => [MySQL::class, PostgreSQL::class, MsSql::class, Liquibase::class],
            'devops_and_cloud' => [
                AWS::class,
                Azure::class,
                AzurePipelines::class,
                Docker::class,
                Git::class,
            ],
            'ai_assisted_engineering' => [
                Claude::class,
                Cursor::class,
                GitHubCopilot::class,
                Gemini::class,
            ],
        ];
    }

    public function getArchitectureFocus(): array
    {
        return [
            'Legacy Modernization (PHP 5.x to 8.x / Angular upgrades)',
            'Large-scale Database Schema Normalization & Query Tuning',
            'CI/CD Automation, Liquibase Database Migrations & Cloud Deployment',
            'High-throughput REST & GraphQL Microservices',
            'AI-Augmented Full-Stack Development Workflows',
        ];
    }
}
