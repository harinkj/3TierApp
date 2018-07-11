# 3TierApp
A 3 tier application with Angular, Spring Boot a Oracle DB

# Oracle DB 
create table "SONARID"."APPLICATIONS"(
        "ID" NUMBER not null,
       "APPNAME" VARCHAR2(255) not null,
       "APPDESCRIPTION" VARCHAR2(255),
       "STAKEHOLDER" VARCHAR2(255) not null,
        constraint "SYS_C0012366" primary key ("ID")
    );
 
    create unique index "SONARID"."SYS_C0012366" on "SONARID"."APPLICATIONS"("ID");
