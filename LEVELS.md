# Maturity Levels

Here are the maturity levels. This is what we use as maturity levels and you may change or reorder items in each level.

## Level 1

|**Items**          | **Description** |
|**[T001]({{ site.baseurl }}{% link catalog/test/T001.md%})**| Measure Test Coverage On Commit Stage. |
|**[T005]({{ site.baseurl }}{% link catalog/test/T005.md%})**| Incremental Commit Stage Test Coverage > 10%. |
|**[B001]({{ site.baseurl }}{% link catalog/build_ci/B001.md%})**| All CI/CD scripts are in VC (CI Config in Code). |
|**[T016]({{ site.baseurl }}{% link catalog/test/T016.md%})**| No Release with Red Tests. |

## Level 2

|**Items**          | **Description** |
|**[T006]({{ site.baseurl }}{% link catalog/test/T006.md%})**| Incremental Commit Stage Test Coverage > 50%. |
|**[T002]({{ site.baseurl }}{% link catalog/test/T002.md%})**| Commit Stage Test Coverage > 10% (At Least Daily). |
|**[T007]({{ site.baseurl }}{% link catalog/test/T007.md%})**| Classify Tests as Commit, Acceptance and (Performance).|
|**[T011]({{ site.baseurl }}{% link catalog/test/T011.md%})**| Acceptance Tests For at Least One Feature Upon Main Use Cases (Fully Automated in CI Script). |
|**[B002]({{ site.baseurl }}{% link catalog/build_ci/B002.md%})**| Automated Code Style Checking. |
|**[B004]({{ site.baseurl }}{% link catalog/build_ci/B004.md%})**| Prevent Compiler Warning Automatically.|
|**[E001]({{ site.baseurl }}{% link catalog/environment/E001.md%})**| All Direct External Dependencies for The Software Product Are Specified using Fixed Versions in Version Control and also Managed with Tools/Scripts in Version Control. |
|**[E012]({{ site.baseurl }}{% link catalog/environment/E012.md%})**| Do Not Store Your Secrets in Your Version Control. |
|**[D001]({{ site.baseurl }}{% link catalog/delivery/D001.md%})**|Deployment Frequency is Once Per Month. |
|**[D005]({{ site.baseurl }}{% link catalog/delivery/D005.md%})**| Lead Time for Changes is Less Than Six Months.|
|**[D009]({{ site.baseurl }}{% link catalog/delivery/D009.md%})**| Time to Restore Service is Less Than One Month.|
|**[D013]({{ site.baseurl }}{% link catalog/delivery/D013.md%})**| Change Failure Rate Less Than 60 Percent.|

## Level 3

|**Items**          | **Description** |
|**[T003]({{ site.baseurl }}{% link catalog/test/T003.md%})**| Commit Stage Test Coverage > 50%. |
|**[B005]({{ site.baseurl }}{% link catalog/build_ci/B005.md%})**| Actively Use Available Analysis Tools On New Code As Submit Gate (50% of sonar-way, Incremental, Zero Issue).|
|**[T012]({{ site.baseurl }}{% link catalog/test/T012.md%})**| Acceptance Tests For Each New Feature.|
|**[T013]({{ site.baseurl }}{% link catalog/test/T013.md%})**| Requirement - Acceptance Test Mapping > 5%. |
|**[E002]({{ site.baseurl }}{% link catalog/environment/E002.md%})**| Automated Application Deployment From Scratch. |
|**[E003]({{ site.baseurl }}{% link catalog/environment/E003.md%})**| Automated Application Upgrade. 
|**[E013]({{ site.baseurl }}{% link catalog/environment/E013.md%})**| All Configuration In Version Control & All Production Cofigs From Version Control. |
|**[E006]({{ site.baseurl }}{% link catalog/environment/E006.md%})**| Data Is Migrated Using Versioned Script Only.|
|**[D002]({{ site.baseurl }}{% link catalog/delivery/D002.md%})**| Deployment Frequency is Once Per Week. |
|**[D006]({{ site.baseurl }}{% link catalog/delivery/D006.md%})**| Lead Time for Changes is Less Than One Month. |
|**[D010]({{ site.baseurl }}{% link catalog/delivery/D010.md%})**| Time to Restore Service is Less Than One Week. |
|**[D014]({{ site.baseurl }}{% link catalog/delivery/D014.md%})**| Change Failure Rate Is Less Than 45 Percent. |
|**[E010]({{ site.baseurl }}{% link catalog/environment/E010.md%})**| Same Process (scripts) To Deploy To Every Environment. |

## Level 4

|**Items**          | **Description** |
|**[T004]({{ site.baseurl }}{% link catalog/test/T004.md%})**| Commit Stage Test Coverage > 60%. |
|**[T014]({{ site.baseurl }}{% link catalog/test/T014.md%})**| Requirement - Acceptance Test Mapping > 20%. |
|**[B006]({{ site.baseurl }}{% link catalog/build_ci/B006.md%})**| Actively Use Available Analysis Tools (80% sonar-way). |
|**[B007]({{ site.baseurl }}{% link catalog/build_ci/B007.md%})**| Build Environment Can Be Automatically Created From Version Control. |
|**[E004]({{ site.baseurl }}{% link catalog/environment/E004.md%})**| Automated Infrastructure Provisioning From Scratch. |
|**[E007]({{ site.baseurl }}{% link catalog/environment/E007.md%})**| Automated Data Migration While Deploying. |
|**[E005]({{ site.baseurl }}{% link catalog/environment/E005.md%})**| Automated Infrastructure Upgrade. |
|**[E014]({{ site.baseurl }}{% link catalog/environment/E014.md%})**| All Transitive Dependency Versions of Direct External Dependencies (related to item E001) Should be Defined. |
|**[D003]({{ site.baseurl }}{% link catalog/delivery/D003.md%})**| Deployment Frequency Is Once Per Day. |
|**[D007]({{ site.baseurl }}{% link catalog/delivery/D007.md%})**| Lead Time For Changes Is Less Than One Day. |
|**[D011]({{ site.baseurl }}{% link catalog/delivery/D011.md%})**| Time To Restore Service Is Less Than One Day. |
|**[D015]({{ site.baseurl }}{% link catalog/delivery/D015.md%})**| Change Failure Rate Is Less Than 15 Percent. |



## Level 5

|**Items**          | **Description** |
|**[T015]({{ site.baseurl }}{% link catalog/test/T015.md%})**| Requirement - Acceptance Test Mapping > 50%. |
|**[E008]({{ site.baseurl }}{% link catalog/environment/E008.md%})**| Data Migration Is Tested. |
|**[D004]({{ site.baseurl }}{% link catalog/delivery/D004.md%})**| Deployment Frequency Is On-Demand (Multiple Deploy Per Day). |
|**[D008]({{ site.baseurl }}{% link catalog/delivery/D008.md%})**| Lead Time For Changes Is Less Than One Hour. |
|**[D012]({{ site.baseurl }}{% link catalog/delivery/D012.md%})**| Time To Restore Service Is Less Than One Hour. |
|**[E009]({{ site.baseurl }}{% link catalog/environment/E009.md%})**| Ability To Automatic Data Migration Roll Back. |