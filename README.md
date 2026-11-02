#  *Simple Todo*

**Simple Todo** is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

## Learning Attainment & Objectives

### State Durability & Persistence Engineering
* **state-persistence** — Engineered data durability mechanisms to ensure user records survived application destruction and device restarts.
* **data-serialization** — Programmatically parsed and transformed volatile runtime object arrays into persistent local storage formats.
* **state-synchronization** — Immediately updated the backing storage layer file arrays simultaneously with UI database mutations.
* **local-data-storage** — Managed direct, on-device file writing or database transactions without relying on an external network host.

### Inter-Process Communication & View Architecture
* **intent-pipeline-engineering** — Constructed programmatic Intent wrappers to pass data payloads safely between distinct screen lifecycles.
* **multi-view-architecture** — Segregated core user interactions across discrete view boundaries (Main List Screen vs. Modal Edit Screen).
* **state-transition-governance** — Managed the exact lifecycles of parent and child views to prevent data loss during backward screen navigation.
* **data-binding** — Programmatically bound internal local memory string configurations to active front-end UI list elements.

### Functional Operations & Data Handling
* **crud-operations** — Architected the fundamental structural cycle of data management: Create, Read, Update, and Delete actions.
* **data-handling-constraints** — Enforced client-side validation rules ensuring modified data mutations mapped precisely to the target item index.
* **array-manipulation** — Executed sequential array indices mapping, deletions, and insertions inside local runtime memory.
* **event-driven-programming** — Implemented local interface event listeners to trigger immediate backend structural changes upon tactile inputs (taps/holds).

### Software Engineering & Lifecycle Governance
* **rapid-prototyping** — Designed, deployed, tested, and confirmed a complete functional local utility under a tight 5-hour time constraint.
* **resource-constrained-development** — Delivered bug-free, functional data isolation code under explicit temporal development limits.
* **software-integration** — Programmatically aligned core Java language structures with Android native list containers and view components.
* **systems-validation** — Tested a finished multi-view CRUD cycle to confirm data integrity remained unbroken across all user state transformations.

### Computing Foundations & Interface Layouts
* **view-recycling-mechanics** — Leveraged dynamic adapter architectures to efficiently handle, re-use, and render rows within memory bounds.
* **mobile-architecture** — Managed activity context frames, memory limits, and view lifecycles within a native mobile OS environment.
* **object-oriented-programming** — Utilized class encapsulation, method overrides, and instantiation rules to configure custom application views.
* **deterministic-state-control** — Designed a completely predictable local system loop where the UI perfectly reflected the underlying dataset state.

## User Stories

The following **required** functionality is completed:

* [X] User can **view a list of todo items**
* [X] User can **successfully add and remove items** from the todo list
* [X] User's **list of items persisted** upon modification and retrieved properly on app restart

The following **optional** features are implemented:

* [X] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list

The following **additional** features are implemented:

* [ ] User can **view a list of removed todo items**
* [ ] User can **unremove removed todo items**
* [ ] User can **create multiple todo lists**
* [ ] User can **rename their todo lists**

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='Walkthrough1.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

While building the app, I faced a challenge regarding the *readLines* and *writeLines* function. To correct this issue, the FileUtils Import statement **import android.os.FileUtils;** was replaced with **import org.apache.commons.io.FileUtils;** at the top of the MainActivity.java file.

## License

    Copyright [2021] [Angelica Magnussen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
