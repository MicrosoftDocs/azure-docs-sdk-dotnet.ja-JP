<Type Name="IWithAppSettings&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithAppSettings&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAppSettings&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAppSettings`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithAppSettings`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAppSettings(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithAppSettings&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT"><span data-ttu-id="07081-101">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="07081-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="07081-102">設定するアプリの設定を許可する、web アプリ定義段階です。</span><span class="sxs-lookup"><span data-stu-id="07081-102">A web app definition stage allowing app settings to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAppSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithAppSetting (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithAppSetting(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithAppSettings`1.WithAppSetting(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAppSetting (key As String, value As String) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAppSetting : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithAppSetting (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="07081-103">アプリ設定のキー。</span><span class="sxs-lookup"><span data-stu-id="07081-103">The key for the app setting.</span></span></param>
        <param name="value"><span data-ttu-id="07081-104">アプリ設定の値です。</span><span class="sxs-lookup"><span data-stu-id="07081-104">The value for the app setting.</span></span></param>
        <summary>
            <span data-ttu-id="07081-105">Web アプリにアプリ設定を追加します。</span><span class="sxs-lookup"><span data-stu-id="07081-105">Adds an app setting to the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="07081-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="07081-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithAppSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithAppSettings (System.Collections.Generic.IDictionary&lt;string,string&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithAppSettings(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithAppSettings`1.WithAppSettings(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAppSettings (settings As IDictionary(Of String, String)) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAppSettings : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithAppSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="07081-107">アプリの設定のマップ。</span><span class="sxs-lookup"><span data-stu-id="07081-107">A  Map of app settings.</span></span></param>
        <summary>
            <span data-ttu-id="07081-108">マップとして、web アプリのアプリの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="07081-108">Specifies the app settings for the web app as a  Map.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="07081-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="07081-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyAppSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithStickyAppSetting (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithStickyAppSetting(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithAppSettings`1.WithStickyAppSetting(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyAppSetting (key As String, value As String) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyAppSetting : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithStickyAppSetting (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="07081-110">アプリ設定のキー。</span><span class="sxs-lookup"><span data-stu-id="07081-110">The key for the app setting.</span></span></param>
        <param name="value"><span data-ttu-id="07081-111">アプリ設定の値です。</span><span class="sxs-lookup"><span data-stu-id="07081-111">The value for the app setting.</span></span></param>
        <summary>
            <span data-ttu-id="07081-112">Web アプリにアプリ設定を追加します。</span><span class="sxs-lookup"><span data-stu-id="07081-112">Adds an app setting to the web app.</span></span> <span data-ttu-id="07081-113">このアプリの設定は、デプロイ スロットをスワップした後もスワップされます。</span><span class="sxs-lookup"><span data-stu-id="07081-113">This app setting will be swapped as well after a deployment slot swap.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="07081-114">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="07081-114">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyAppSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithStickyAppSettings (System.Collections.Generic.IDictionary&lt;string,string&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithStickyAppSettings(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithAppSettings`1.WithStickyAppSettings(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyAppSettings (settings As IDictionary(Of String, String)) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyAppSettings : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithStickyAppSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="07081-115">アプリの設定のマップ。</span><span class="sxs-lookup"><span data-stu-id="07081-115">A  Map of app settings.</span></span></param>
        <summary>
            <span data-ttu-id="07081-116">マップとして、web アプリのアプリの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="07081-116">Specifies the app settings for the web app as a  Map.</span></span> <span data-ttu-id="07081-117">これらのアプリの設定は、デプロイ スロットをスワップした後もスワップされます。</span><span class="sxs-lookup"><span data-stu-id="07081-117">These app settings will be swapped as well after a deployment slot swap.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="07081-118">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="07081-118">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>