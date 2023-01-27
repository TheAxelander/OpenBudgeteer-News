<html>
    <body>
<div class="card mb-3">
    <div class="card-header">
        <h5>Update 1.6.3 released</h5>
        <div class="text-muted">2023-01-27</div>
    </div>
    <div class="card-body">
        <div class="row">
             <p align="center">
                <img class="img-fluid" alt="Pre-release Badge" src="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/update-1.6.3.png">
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
                <img class="img-fluid" alt="Pre-release Badge" src="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/update-1.6.2.png">
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
                <img class="img-fluid" alt="Pre-release Badge" src="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/update-1.6.1_2.png">
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
<div class="card mb-3">
    <div class="card-header">
        <h5>Update 1.6 released</h5>
        <div class="text-muted">2022-12-03</div>
    </div>
    <div class="card-body">
        <div class="row">
            <p align="center">
                <img class="img-fluid" alt="Pre-release Badge" src="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/update-1.6.png">
            </p>
            <p class="card-text">
                OpenBudgeteer 1.6 is now available with new features, optimizations and some fixes. Check out the Changelog for the full list of changes. Below some highlights of the new update:
            </p>
            <h5>Recurring Transactions & Split</h5>
            <p align="center">
                <a href="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/2022-12-03-001.png" target="_blank">
                    <img class="img-fluid img-thumbnail" alt="Pre-release Badge" src="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/2022-12-03-001.png">
                </a>
            </p>
            <p class="card-text">
                It's now possible to manually split a Bank Transaction into multiple Buckets. In addition, if the amount assigned to a Bucket is lower than the Transaction itself, the remaining amount is displayed. Thanks a lot to <a href="https://github.com/ambroser1971">Rich Ambrose</a> for implementing this feature.
            </p>
            <p class="card-text">
                Creation of Recurring Transactions has been added too. This is useful if you mainly add your Bank Transactions manually instead of importing txt/csv files.
            </p>
            <h5>Themes</h5>
            <p align="center">
                <a href="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/2022-12-03-002.png" target="_blank">
                    <img class="img-fluid img-thumbnail" alt="Pre-release Badge" src="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/2022-12-03-002.png">
                </a>
            </p>
            <p align="center">
                <a href="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/2022-12-03-003.png" target="_blank">
                    <img class="img-fluid img-thumbnail" alt="Pre-release Badge" src="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/2022-12-03-003.png">
                </a>
            </p>
            <p align="center">
                <a href="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/2022-12-03-004.png" target="_blank">
                    <img class="img-fluid img-thumbnail" alt="Pre-release Badge" src="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/2022-12-03-004.png">
                </a>
            </p>
            <p class="card-text">
                Themes are now supported. Visit <a href="https://bootswatch.com">Bootswatch</a> for more details. To select a theme use the new option APPSETTINGS_THEME as docker environment variable or in the appsettings.json file.
            </p>
            <h5>Import Page Redesign</h5>
            <p align="center">
                <a href="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/2022-12-03-005.png" target="_blank">
                    <img class="img-fluid img-thumbnail" alt="Pre-release Badge" src="https://raw.githubusercontent.com/TheAxelander/OpenBudgeteer-News/main/images/2022-12-03-005.png">
                </a>
            </p>
            <p class="card-text">
                Import page got some slight redesign. You can now switch between all steps in an accordion view, where each section is enabled depending on your input.
            </p>
            <h5>News Feed</h5>
            <p class="card-text">
                And as you might noticed this news overview has been introduced with 1.6 to give you more regular updates on current development and upcoming things.
            </p>
        </div>
    </div>
</div>

</body>
</html>