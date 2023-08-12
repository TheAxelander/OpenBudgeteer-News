<html>
    <body>
<div class="card mb-3">
    <div class="card-header">
        <h5>Upcoming Update 1.7</h5>
        <div class="text-muted">2023-08-12</div>
    </div>
    <div class="card-body">
        <div class="row">
             <p align="center">
                <img class="img-fluid" src="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/notes-for-update-1.7">
            </p>
            <p class="card-text">
                I plan to release Update 1.7 within the next days which includes some major changes on data in the underlying database. During the last months I tried to test as much as possible, but of course it can happen that I missed one or the other spot which might lead to some data corruption. For that reason, my highly recommendation is:
            </p>
            <p class="card-text">
                Please backup your data before updating to 1.7!!!
            </p>
            <p class="card-text">
                Of course, this would apply to every update, but this time it's more important as some data migration will happen during first startup. If something goes wrong after the update or some values/calculations show different results, please create an issue on GitHub and I try to resolve it on short notice.
            </p>
            <p class="card-text">
                In the meantime, you can restore the data and switch the Docker image tag from "latest" to "1.6.3".
            </p>
            <p class="card-text">
                In case you already want to test the migration, feel free to use the "pre-release" tag.
            </p>
        </div>
    </div>
</div>    
<div class="card mb-3">
    <div class="card-header">
        <h5>Update 1.6.3 released</h5>
        <div class="text-muted">2023-01-27</div>
    </div>
    <div class="card-body">
        <div class="row">
             <p align="center">
                <img class="img-fluid" src="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/update-1.6.3.png">
            </p>
            <p class="card-text">
                As already accouned in the previous update, version 1.6.3 now contains some fixes and improvements for Import Profile handling and the Import Page itself.
            </p>
        </div>
    </div>
</div>
<div class="card mb-3">
    <div class="card-header">
        <h5>Update 1.6.2 released</h5>
        <div class="text-muted">2023-01-11</div>
    </div>
    <div class="card-body">
        <div class="row">
             <p align="center">
                <img class="img-fluid" src="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/update-1.6.2.png">
            </p>
            <p class="card-text">
                A quick fix has been released after identifying an issue for Column mappings on Import Page. This one was appearing after implementing the latest fix for Firefox, but it should be resolved now.
            </p>
            <p class="card-text">
                Beside that there is still some unexpected bahaviour in updating and deleting Import Profiles which I want to fix and improve in an upcoming 1.6.3 release.
            </p>
        </div>
    </div>
</div>
<div class="card mb-3">
    <div class="card-header">
        <h5>Update 1.6.1 released</h5>
        <div class="text-muted">2022-12-31</div>
    </div>
    <div class="card-body">
        <div class="row">
             <p align="center">
                <img class="img-fluid" src="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/update-1.6.1_2.png">
            </p>
            <p class="card-text">
                Update 1.6.1 has been released which fixes the rendering issue on Firefox.
            </p>
        </div>
    </div>
</div> 
<div class="card mb-3">
    <div class="card-header">
        <h5>Known issue - Rendering of Drop-down selection for Firefox</h5>
        <div class="text-muted">2022-12-12</div>
    </div>
    <div class="card-body">
        <div class="row">
            <p class="card-text">
                There is currently an issue using OpenBudgeteer with Firefox. In some circumstances the selection of items in a drop-down list is not working properly. The Backend is using the right selection/value but the UI shows a wrong selection/value. So this is overall just a visual issue but of course very confusing and not really usable.
            </p>
            <p class="card-text">
                The bug is currently tracked via <a href="https://github.com/TheAxelander/OpenBudgeteer/issues/114">Issue #114</a> and quite known for Firefox (see <a href="https://stackoverflow.com/questions/68134956/firefox-and-selected-selected">here</a>)
            </p>
            <p class="card-text">
                A fix has been implemented on <strong>pre-release</strong>, due to the fact that it affects all Drop-downs in the whole application, I would like to spend more time on UI testing before releasing it.
            </p>
        </div>
    </div>
</div>
</body>
</html>