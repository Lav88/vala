<template>
    <ul class="main-menu nav">
        <li>
            <n-link to="/">Home</n-link>
        </li>
        <li class="has-submenu">
            <n-link to="/about">About Us</n-link>
            <ul class="submenu-nav">
                <li>
                    <n-link to="/about">Vision &amp; Mission</n-link>
                </li>
                <li>
                    <n-link to="/causes-details">Sponsors</n-link>
                </li>
            </ul>
        </li>
        <li class="has-submenu">
            <n-link to="/event-details">AfrikaTage</n-link>
            <ul class="submenu-nav">
                <li>
                    <n-link to="/event-details">AfrikaTage 2022</n-link>
                </li>
                <li>
                    <n-link to="/volunteer">Volunteer</n-link>
                </li>
            </ul>
        </li>
        <li class="has-submenu">
            <n-link to="/causes-details">FC Vala</n-link>
            <ul class="submenu-nav">
                <li>
                    <n-link to="/causes-details">Speil Plan</n-link>
                </li>
                <li>
                    <n-link to="/das-team">Das Team</n-link>
                </li>
            </ul>
        </li>
        <li class="has-submenu">
            <n-link to="/causes">Cafe Afrika</n-link>
            <ul class="submenu-nav">
                <li>
                    <n-link to="/causes">All Cafe Events</n-link>
                </li>
                <li>
                    <n-link to="/cafe-details">Upcoming Event</n-link>
                </li>
            </ul>
        </li>
        <li class="has-submenu">
            <n-link to="/blog">Events</n-link>
            <ul class="submenu-nav">
                <li>
                    <n-link to="/blog">Blog</n-link>
                </li>
                <li>
                    <n-link to="/blog-details">Blog Details</n-link>
                </li>
                <li>
                    <n-link to="/donation">Donation</n-link>
                </li>
            </ul>
        </li>
        <li>
            <n-link to="/contact">Kontakt</n-link>
        </li>
    </ul>
</template>