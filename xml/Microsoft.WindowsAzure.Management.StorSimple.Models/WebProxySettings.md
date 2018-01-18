<Type Name="WebProxySettings" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.WebProxySettings">
  <TypeSignature Language="C#" Value="public class WebProxySettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebProxySettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.WebProxySettings" />
  <TypeSignature Language="VB.NET" Value="Public Class WebProxySettings" />
  <TypeSignature Language="F#" Value="type WebProxySettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="03736-101">デバイスのため、WebProxy 設定</span><span class="sxs-lookup"><span data-stu-id="03736-101">Device WebProxy settings</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebProxySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.WebProxySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="03736-102">WebProxySettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="03736-102">Initializes a new instance of the WebProxySettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebProxySettings (Microsoft.WindowsAzure.Management.StorSimple.Models.AuthenticationType authentication, string connectionURI, string username);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.AuthenticationType authentication, string connectionURI, string username) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.WebProxySettings.#ctor(Microsoft.WindowsAzure.Management.StorSimple.Models.AuthenticationType,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (authentication As AuthenticationType, connectionURI As String, username As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.WebProxySettings : Microsoft.WindowsAzure.Management.StorSimple.Models.AuthenticationType * string * string -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.WebProxySettings" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.WebProxySettings (authentication, connectionURI, username)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authentication" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.AuthenticationType" />
        <Parameter Name="connectionURI" Type="System.String" />
        <Parameter Name="username" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authentication">To be added.</param>
        <param name="connectionURI">To be added.</param>
        <param name="username">To be added.</param>
        <summary>
            <span data-ttu-id="03736-103">必須の引数で WebProxySettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="03736-103">Initializes a new instance of the WebProxySettings class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authentication">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.AuthenticationType Authentication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.AuthenticationType Authentication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.WebProxySettings.Authentication" />
      <MemberSignature Language="VB.NET" Value="Public Property Authentication As AuthenticationType" />
      <MemberSignature Language="F#" Value="member this.Authentication : Microsoft.WindowsAzure.Management.StorSimple.Models.AuthenticationType with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.WebProxySettings.Authentication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.AuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="03736-104">必須。</span><span class="sxs-lookup"><span data-stu-id="03736-104">Required.</span></span> <span data-ttu-id="03736-105">取得または認証の設定</span><span class="sxs-lookup"><span data-stu-id="03736-105">Gets or sets the Authentication</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionURI">
      <MemberSignature Language="C#" Value="public string ConnectionURI { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionURI" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.WebProxySettings.ConnectionURI" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionURI As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionURI : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.WebProxySettings.ConnectionURI" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="03736-106">必須。</span><span class="sxs-lookup"><span data-stu-id="03736-106">Required.</span></span> <span data-ttu-id="03736-107">取得または設定の接続 URI</span><span class="sxs-lookup"><span data-stu-id="03736-107">Gets or sets the Connection URI</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.WebProxySettings.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.WebProxySettings.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="03736-108">必須。</span><span class="sxs-lookup"><span data-stu-id="03736-108">Required.</span></span> <span data-ttu-id="03736-109">取得または設定、ユーザー名</span><span class="sxs-lookup"><span data-stu-id="03736-109">Gets or sets the Username</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>