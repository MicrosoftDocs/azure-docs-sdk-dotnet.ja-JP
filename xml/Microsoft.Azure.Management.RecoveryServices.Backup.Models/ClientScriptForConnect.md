<Type Name="ClientScriptForConnect" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect">
  <TypeSignature Language="C#" Value="public class ClientScriptForConnect" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClientScriptForConnect extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect" />
  <TypeSignature Language="VB.NET" Value="Public Class ClientScriptForConnect" />
  <TypeSignature Language="F#" Value="type ClientScriptForConnect = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7393a-101">クライアント スクリプト ファイルの詳細/フォルダーを復元します。</span><span class="sxs-lookup"><span data-stu-id="7393a-101">Client script details for file / folder restore.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientScriptForConnect ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7393a-102">ClientScriptForConnect クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7393a-102">Initializes a new instance of the ClientScriptForConnect class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientScriptForConnect (string scriptContent = null, string scriptExtension = null, string osType = null, string url = null, string scriptNameSuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string scriptContent, string scriptExtension, string osType, string url, string scriptNameSuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional scriptContent As String = null, Optional scriptExtension As String = null, Optional osType As String = null, Optional url As String = null, Optional scriptNameSuffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect : string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect (scriptContent, scriptExtension, osType, url, scriptNameSuffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scriptContent" Type="System.String" />
        <Parameter Name="scriptExtension" Type="System.String" />
        <Parameter Name="osType" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="scriptNameSuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scriptContent"><span data-ttu-id="7393a-103">ファイル用のクライアント スクリプトの内容をファイル/フォルダーを復元します。</span><span class="sxs-lookup"><span data-stu-id="7393a-103">File content of the client script for file / folder restore.</span></span></param>
        <param name="scriptExtension"><span data-ttu-id="7393a-104">ファイル用のクライアント スクリプトの拡張機能のファイル/フォルダーの復元 - .ps1 .sh などです。</span><span class="sxs-lookup"><span data-stu-id="7393a-104">File extension of the client script for file / folder restore - .ps1 , .sh , etc.</span></span></param>
        <param name="osType"><span data-ttu-id="7393a-105">OS の種類 - Windows、Linux など対象のファイル/フォルダーの復元のクライアント スクリプトの動作です。</span><span class="sxs-lookup"><span data-stu-id="7393a-105">OS type - Windows, Linux etc. for which this file / folder restore client script works.</span></span></param>
        <param name="url"><span data-ttu-id="7393a-106">URL の実行可能ファイル コンテンツのソースの場所から。</span><span class="sxs-lookup"><span data-stu-id="7393a-106">URL of Executable from where to source the content.</span></span> <span data-ttu-id="7393a-107">これが null でない場合、ScriptContent は適していません。</span><span class="sxs-lookup"><span data-stu-id="7393a-107">If this is not null then ScriptContent should not be used</span></span></param>
        <param name="scriptNameSuffix"><span data-ttu-id="7393a-108">ユーザーにダウンロードしたスクリプトの名前に追加する必要があります必須サフィックスです。</span><span class="sxs-lookup"><span data-stu-id="7393a-108">Mandator suffix that should be added to the name of script that is given for download to user.</span></span>
            <span data-ttu-id="7393a-109">場合は、null または空し、それを無視します。</span><span class="sxs-lookup"><span data-stu-id="7393a-109">If its null or empty then , ignore it.</span></span></param>
        <summary>
            <span data-ttu-id="7393a-110">ClientScriptForConnect クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7393a-110">Initializes a new instance of the ClientScriptForConnect class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public string OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As String" />
      <MemberSignature Language="F#" Value="member this.OsType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7393a-111">取得または設定の OS の種類 - Windows、Linux など対象のファイル/フォルダーの復元のクライアント スクリプトの動作です。</span><span class="sxs-lookup"><span data-stu-id="7393a-111">Gets or sets OS type - Windows, Linux etc. for which this file / folder restore client script works.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptContent">
      <MemberSignature Language="C#" Value="public string ScriptContent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptContent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptContent" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptContent As String" />
      <MemberSignature Language="F#" Value="member this.ScriptContent : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptContent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scriptContent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7393a-112">取得またはファイル用のクライアント スクリプトのファイルの内容を設定/フォルダーを復元します。</span><span class="sxs-lookup"><span data-stu-id="7393a-112">Gets or sets file content of the client script for file / folder restore.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptExtension">
      <MemberSignature Language="C#" Value="public string ScriptExtension { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptExtension" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptExtension" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptExtension As String" />
      <MemberSignature Language="F#" Value="member this.ScriptExtension : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptExtension" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scriptExtension")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7393a-113">取得または設定ファイル用のクライアント スクリプトのファイル拡張子とフォルダーの復元 - .ps1 .sh などです。</span><span class="sxs-lookup"><span data-stu-id="7393a-113">Gets or sets file extension of the client script for file / folder restore - .ps1 , .sh , etc.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptNameSuffix">
      <MemberSignature Language="C#" Value="public string ScriptNameSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptNameSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptNameSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptNameSuffix As String" />
      <MemberSignature Language="F#" Value="member this.ScriptNameSuffix : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptNameSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scriptNameSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7393a-114">取得またはダウンロードするユーザーが指定されたスクリプトの名前に追加する必要があります必須サフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="7393a-114">Gets or sets mandator suffix that should be added to the name of script that is given for download to user.</span></span>
            <span data-ttu-id="7393a-115">場合は、null または空し、それを無視します。</span><span class="sxs-lookup"><span data-stu-id="7393a-115">If its null or empty then , ignore it.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7393a-116">取得またはコンテンツのソースの場所から実行可能ファイルの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="7393a-116">Gets or sets URL of Executable from where to source the content.</span></span> <span data-ttu-id="7393a-117">これが null でない場合、ScriptContent は適していません。</span><span class="sxs-lookup"><span data-stu-id="7393a-117">If this is not null then ScriptContent should not be used</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>