<article>
    <section>
        <div>
            <div>
                <div>
                    <article>
                        <div>
                            <div>
                                <div>
                                    <h1 itemprop="headline">osTicket</h1>
                                </div>
                                <div><br></div>
                            </div>
                            <div>
                                <div>
                                    <div>
                                        <div>
                                            <div>
                                                <div>
                                                    <div>
                                                        <div>
                                                            <figure>
                                                                <div>
                                                                    <div><img alt="" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/4364b0d2-62c5-4fec-b59c-d474271ea978/osticket-supsys-sm.png?format=750w"></div>
                                                                </div>
                                                            </figure>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <p>For this lab I wanted to learn how to set up a ticketing system and then explore its capabilities. I&rsquo;ve had some previous experience learning the Spiceworks ticketing system, however, this osTicket project gave me some knowledge on the backend set up of a ticketing system. This won&rsquo;t be an extremely detailed walkthrough as I am providing a vague demonstration of my experience setting up and running my own ticketing system.</p>
                                                        <p><br></p>
                                                        <p><strong>Environments and Technologies Used</strong></p>
                                                        <ul>
                                                            <li>
                                                                <p>Microsoft Azure (Virtual Machines)</p>
                                                            </li>
                                                            <li>
                                                                <p>Remote Desktop</p>
                                                            </li>
                                                            <li>
                                                                <p>Internet Information Services</p>
                                                            </li>
                                                        </ul>
                                                        <p>Operating Systems</p>
                                                        <ul>
                                                            <li>
                                                                <p>Windows 10</p>
                                                            </li>
                                                        </ul>
                                                        <p><br></p>
                                                        <p>Prerequisites: You must download and install the following files, in the pic below, for the osTicket installation to work. Also Internet Information Services (IIS) should be enabled. This can be done by navigating to and turning on CGI under windows Programs and Features. You will know if IIS is working properly if you enter 127.0.0.1 localhost address into your web browser and the IIS site appears. Putting osTicket together is a lengthy process, but it gives you a glimpse into what it may be like for an admin to install and run it for an organization. &nbsp;</p>
                                                        <div><svg>
                                                                <path d="M0,22.5 L296.85,22.5"></path>
                                                            </svg></div>
                                                        <div><svg>
                                                                <path d="M0,22.5 L141.85,22.5"></path>
                                                            </svg></div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <div>
                                                            <figure>
                                                                <div>
                                                                    <div><img alt="" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/c97e03fb-7342-43d8-8d02-92988d1b3d91/osticket+screenshot+1.jpg?format=1000w"></div>
                                                                </div>
                                                            </figure>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <p><br></p>
                                                        <p>Nearing the end of the installation, you should be able to search for the IIS Manager in your Windows search bar and click &nbsp;*.80 (http) on the right, and the osTicket installation webpage should appear.</p>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <div>
                                                            <figure>
                                                                <div>
                                                                    <div><img alt="" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/68947605-9810-4af5-abea-ad8ca2045fe1/osticket+screenshot+2.jpg?format=1000w"></div>
                                                                </div>
                                                            </figure>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <p><br></p>
                                                        <p>When you first encounter the ticketing system, be aware of the panel you reside in. There is the Admin Panel and the Agent Panel. You can navigate between the two at the top right of your screen. Most configuration will be done in the Admin Panel.</p>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <div>
                                                            <div>
                                                                <div><img alt="osticket+screenshot+3+%28agent+panel%29.jpg" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1678115566779-VTHAF0BYTDEI3LVQO12X/osticket%2Bscreenshot%2B3%2B%2528agent%2Bpanel%2529.jpg?format=1000w"><img alt="osticket%2Bscreenshot%2B4%2B%2528admin%2Bpanel%2529.jpg" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1678115819651-6EQ0XCOWYIYYU7N6FLVD/osticket%252Bscreenshot%252B4%252B%252528admin%252Bpanel%252529.jpg?format=1000w"></div>
                                                            </div>
                                                            <div>
                                                                <div><a tabindex="0"></a><a tabindex="0"></a></div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <p><br></p>
                                                        <p>Now we will delve into just how every helpdesk employee (also referred to as agents) is categorized into the ticketing system, assigned certain permissions, and given deadlines. Lets start with Roles. You should be under the Admin Panel &gt; Agents &gt; Roles.</p>
                                                        <p><strong>Roles</strong> refer to the permissions given to agents in relation to the department they belong to. Each role comes with a specific set of permissions that can be modified for agents assigned to that role within a department. It is possible to create an unlimited number of roles and assign them to agents with access to different departments.</p>
                                                        <div><svg>
                                                                <path d="M0,22.5 L44.85,22.5"></path>
                                                            </svg></div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <div>
                                                            <figure>
                                                                <div>
                                                                    <div><img alt="" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/5bb6e250-43d4-4428-b7a2-f11181f3bb96/osticket+screenshot+5+%28roles%29.jpg?format=1000w"></div>
                                                                </div>
                                                            </figure>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <p><br></p>
                                                        <p><strong>Departments:&nbsp;</strong>Tickets route through departments in the help desk, therefore each department must come with its own settings.</p>
                                                        <div><svg>
                                                                <path d="M0,22.5 L109.85,22.5"></path>
                                                            </svg></div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <div>
                                                            <figure>
                                                                <div>
                                                                    <div><img alt="" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/dca73c41-5f43-47cb-a7cd-6dfe0adb3a23/osticket+screenshot+5+%28departments%29png.jpg?format=1000w"></div>
                                                                </div>
                                                            </figure>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <p><br></p>
                                                        <p><strong>Teams:</strong> Teams give you the option to bring agents from several departments together and arrange them to address a specific problem or user by means of a help topic or ticket filter.</p>
                                                        <div><svg>
                                                                <path d="M0,22.5 L56.85,22.5"></path>
                                                            </svg></div>
                                                        <div><svg>
                                                                <path d="M0,22.5 L2.8499999999999996,22.5"></path>
                                                            </svg></div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <div>
                                                            <figure>
                                                                <div>
                                                                    <div><img alt="" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/f2098686-35bc-4c71-9e25-60138471daf6/osticket+screenshot+6+%28teams%29.jpg?format=1000w"></div>
                                                                </div>
                                                            </figure>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <p><br></p>
                                                        <p><strong>Agents:&nbsp;</strong>Agents are the help desk professionals who are responsible for resolving tickets. Apart from their primary department, agents can also be given extended access to other departments of the help desk and then be assigned different roles within each departments.</p>
                                                        <div><svg>
                                                                <path d="M0,22.5 L59.85,22.5"></path>
                                                            </svg></div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <div>
                                                            <figure>
                                                                <div>
                                                                    <div><img alt="" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1d8bfe4c-2453-4511-9585-2bd1b9940adc/osticket+screenshot+7+%28agents%29.jpg?format=1000w"></div>
                                                                </div>
                                                            </figure>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <p><br></p>
                                                        <p><strong>Users:</strong> Users are the organization employees who create tickets for the help desk to resolve. These users can be added or deleted from the User Directory of the help desk at any time.&nbsp;</p>
                                                        <div><svg>
                                                                <path d="M0,22.5 L49.85,22.5"></path>
                                                            </svg></div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <div>
                                                            <figure>
                                                                <div>
                                                                    <div><img alt="" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/10d5a79d-0296-4e26-89d3-da6cd80e4547/osticket+screenshot+8+%28Users%29.jpg?format=1000w"></div>
                                                                </div>
                                                            </figure>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <p><br></p>
                                                        <p><strong>SLAs:</strong> Service Level Agreements are meant to establish a specific timeframe in which the help desk administrator needs the tickets to be resolved and closed for the satisfaction of the users and the organization.</p>
                                                        <div><svg>
                                                                <path d="M0,22.5 L47.85,22.5"></path>
                                                            </svg></div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <div>
                                                            <figure>
                                                                <div>
                                                                    <div><img alt="" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/e0f766c6-d3c8-4494-861b-ea694ef62353/osticket+screenshot+9+%28SLA%29.jpg?format=1000w"></div>
                                                                </div>
                                                            </figure>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <p><br></p>
                                                        <p>Help Topics: Help Topics can optimize the help desk experience for end-users by ensuring that tickets are promptly assigned and addressed. They are responsible for assigning the ticket to a specific department and agents who have access to the ticket. Additionally, Help Topics can also control other configurations related to the ticket such as it&rsquo;s SLA and priority level.</p>
                                                        <div><svg>
                                                                <path d="M0,22.5 L96.85,22.5"></path>
                                                            </svg></div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <div>
                                                            <figure>
                                                                <div>
                                                                    <div><img alt="" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/09fea549-78d8-4bec-9646-0d20f750cbfb/osticket+screenshot+10+%28help+topic%29.png?format=1000w"></div>
                                                                </div>
                                                            </figure>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <p>Lastly, we will briefly explore the lifestyle of a ticket slide by slide. (1-4)</p>
                                                        <ol>
                                                            <li>
                                                                <p>The creation of a ticket by our example user, David Danger. The ticket comes with an issue summary and detailed explanation of the problem.</p>
                                                            </li>
                                                            <li>
                                                                <p>The ticket is automatically assigned to me, the admin, for further evaluation.</p>
                                                            </li>
                                                            <li>
                                                                <p>I as the admin, am able to set my personal configurations for the ticket&rsquo;s SLA, priority level, and what user the ticket is currently assigned to. I decide to release myself from the ticket and assign it to Mickey Longtail, my help desk professional who is great with hardware.</p>
                                                            </li>
                                                            <li>
                                                                <p>This thread displays every status update with timestamps on the ticket from start to finish. It also records the communication going on between help desk staff.</p>
                                                            </li>
                                                        </ol>
                                                    </div>
                                                </div>
                                                <div>
                                                    <div>
                                                        <div>
                                                            <div>
                                                                <div><img alt="ticket+lifecycle+1.jpg" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1678123120697-4DPE73AAM6QZCPV4JLCI/ticket%2Blifecycle%2B1.jpg?format=1000w">
                                                                    <div><br></div>
                                                                </div>
                                                                <div><img alt="ticket+lifecycle+3.jpg" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1678123153770-IACNG367OKRUR16Z5LM2/ticket%2Blifecycle%2B3.jpg?format=1000w">
                                                                    <div><br></div>
                                                                </div>
                                                                <div><img alt="ticket+lifecycle+4.jpg" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1678123167353-7D5ZIY662YTRAAOJSCSZ/ticket%2Blifecycle%2B4.jpg?format=1000w">
                                                                    <div><br></div>
                                                                </div>
                                                                <div><img alt="ticket+lifecycle+5.jpg" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1678123182268-VPGIYYILJTMRUWJJGT3S/ticket%2Blifecycle%2B5.jpg?format=1000w">
                                                                    <div><br></div>
                                                                </div>
                                                            </div>
                                                            <div>
                                                                <div><a tabindex="0"></a><a tabindex="0"></a></div>
                                                            </div>
                                                        </div>
                                                        <div>
                                                            <div><img tabindex="0" aria-label="Slide 1" alt="ticket+lifecycle+1.jpg" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1678123120697-4DPE73AAM6QZCPV4JLCI/ticket%2Blifecycle%2B1.jpg?format=300w"><img tabindex="0" aria-label="Slide 2" alt="ticket+lifecycle+3.jpg" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1678123153770-IACNG367OKRUR16Z5LM2/ticket%2Blifecycle%2B3.jpg?format=300w"><img tabindex="0" aria-label="Slide 3" alt="ticket+lifecycle+4.jpg" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1678123167353-7D5ZIY662YTRAAOJSCSZ/ticket%2Blifecycle%2B4.jpg?format=300w"><img tabindex="0" aria-label="Slide 4" alt="ticket+lifecycle+5.jpg" src="https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1678123182268-VPGIYYILJTMRUWJJGT3S/ticket%2Blifecycle%2B5.jpg?format=300w"></div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <section>
                                <div>
                                    <div><br></div>
                                </div>
                            </section>
                        </div>
                    </article>
                </div>
            </div>
        </div>
    </section>
</article>
<section><a href="https://www.malikhudson.tech/projects/windows-server-2016">
        <div>
            <div>Next</div>
        </div>
    </a></section>
