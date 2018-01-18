<Type Name="HostingEnvironmentDeploymentInfo" FullName="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDeploymentInfo">
  <TypeSignature Language="C#" Value="public class HostingEnvironmentDeploymentInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HostingEnvironmentDeploymentInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDeploymentInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class HostingEnvironmentDeploymentInfo" />
  <TypeSignature Language="F#" Value="type HostingEnvironmentDeploymentInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1546b-101">App Service 環境のリソースを作成するために必要な情報です。</span><span class="sxs-lookup"><span data-stu-id="1546b-101">Information needed to create resources on an App Service Environment.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostingEnvironmentDeploymentInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDeploymentInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1546b-102">HostingEnvironmentDeploymentInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1546b-102">Initializes a new instance of the HostingEnvironmentDeploymentInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostingEnvironmentDeploymentInfo (string name = null, string location = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDeploymentInfo.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional location As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDeploymentInfo : string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDeploymentInfo" Usage="new Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDeploymentInfo (name, location)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="1546b-103">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1546b-103">Name of the App Service Environment.</span></span></param>
        <param name="location"><span data-ttu-id="1546b-104">App Service 環境の場所です。</span><span class="sxs-lookup"><span data-stu-id="1546b-104">Location of the App Service Environment.</span></span></param>
        <summary>
            <span data-ttu-id="1546b-105">HostingEnvironmentDeploymentInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1546b-105">Initializes a new instance of the HostingEnvironmentDeploymentInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDeploymentInfo.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDeploymentInfo.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1546b-106">取得または App Service 環境の場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="1546b-106">Gets or sets location of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDeploymentInfo.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDeploymentInfo.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1546b-107">取得または App Service 環境の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="1546b-107">Gets or sets name of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>