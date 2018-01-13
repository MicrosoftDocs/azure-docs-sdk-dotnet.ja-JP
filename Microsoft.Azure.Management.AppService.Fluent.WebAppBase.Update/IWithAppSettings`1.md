<Type Name="IWithAppSettings&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAppSettings&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAppSettings`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1" />
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
    <typeparam name="FluentT"><span data-ttu-id="64987-101">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="64987-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="64987-102">Web アプリは、段階の許可を設定するアプリの設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="64987-102">A web app update stage allowing app settings to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAppSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithAppSetting (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithAppSetting(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1.WithAppSetting(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAppSetting (key As String, value As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAppSetting : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithAppSetting (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="64987-103">アプリ設定のキー。</span><span class="sxs-lookup"><span data-stu-id="64987-103">The key for the app setting.</span></span></param>
        <param name="value"><span data-ttu-id="64987-104">アプリ設定の値です。</span><span class="sxs-lookup"><span data-stu-id="64987-104">The value for the app setting.</span></span></param>
        <summary>
            <span data-ttu-id="64987-105">Web アプリにアプリ設定を追加します。</span><span class="sxs-lookup"><span data-stu-id="64987-105">Adds an app setting to the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="64987-106">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="64987-106">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithAppSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithAppSettings (System.Collections.Generic.IDictionary&lt;string,string&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithAppSettings(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1.WithAppSettings(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAppSettings (settings As IDictionary(Of String, String)) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAppSettings : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithAppSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="64987-107">アプリの設定のマップ。</span><span class="sxs-lookup"><span data-stu-id="64987-107">A  Map of app settings.</span></span></param>
        <summary>
            <span data-ttu-id="64987-108">マップとして、web アプリのアプリの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="64987-108">Specifies the app settings for the web app as a  Map.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="64987-109">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="64987-109">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithAppSettingStickiness">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithAppSettingStickiness (string key, bool sticky);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithAppSettingStickiness(string key, bool sticky) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1.WithAppSettingStickiness(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAppSettingStickiness (key As String, sticky As Boolean) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAppSettingStickiness : string * bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithAppSettingStickiness (key, sticky)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="sticky" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="64987-110">貼り付けを変更するには、アプリ設定のキー。</span><span class="sxs-lookup"><span data-stu-id="64987-110">The key of the app setting to change stickiness.</span></span></param>
        <param name="sticky"><span data-ttu-id="64987-111">アプリ設定が、スロットにスワップの間にスティックする場合は true。</span><span class="sxs-lookup"><span data-stu-id="64987-111">True if the app setting sticks to the slot during a swap.</span></span></param>
        <summary>
            <span data-ttu-id="64987-112">アプリの設定の貼り付けを変更します。</span><span class="sxs-lookup"><span data-stu-id="64987-112">Changes the stickiness of an app setting.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="64987-113">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="64987-113">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAppSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutAppSetting (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutAppSetting(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1.WithoutAppSetting(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAppSetting (key As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutAppSetting : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithoutAppSetting key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="64987-114">アプリの設定を削除するキー。</span><span class="sxs-lookup"><span data-stu-id="64987-114">The key of the app setting to remove.</span></span></param>
        <summary>
            <span data-ttu-id="64987-115">Web アプリからアプリ設定を削除します。</span><span class="sxs-lookup"><span data-stu-id="64987-115">Removes an app setting from the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="64987-116">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="64987-116">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyAppSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithStickyAppSetting (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithStickyAppSetting(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1.WithStickyAppSetting(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyAppSetting (key As String, value As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyAppSetting : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithStickyAppSetting (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="64987-117">アプリ設定のキー。</span><span class="sxs-lookup"><span data-stu-id="64987-117">The key for the app setting.</span></span></param>
        <param name="value"><span data-ttu-id="64987-118">アプリ設定の値です。</span><span class="sxs-lookup"><span data-stu-id="64987-118">The value for the app setting.</span></span></param>
        <summary>
            <span data-ttu-id="64987-119">Web アプリにアプリ設定を追加します。</span><span class="sxs-lookup"><span data-stu-id="64987-119">Adds an app setting to the web app.</span></span> <span data-ttu-id="64987-120">このアプリの設定は、スロットのスワップの間に維持されます。</span><span class="sxs-lookup"><span data-stu-id="64987-120">This app setting will stay at the slot during a swap.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="64987-121">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="64987-121">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyAppSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithStickyAppSettings (System.Collections.Generic.IDictionary&lt;string,string&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithStickyAppSettings(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1.WithStickyAppSettings(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyAppSettings (settings As IDictionary(Of String, String)) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyAppSettings : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithStickyAppSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="64987-122">アプリの設定のマップ。</span><span class="sxs-lookup"><span data-stu-id="64987-122">A  Map of app settings.</span></span></param>
        <summary>
            <span data-ttu-id="64987-123">マップとして、web アプリのアプリの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="64987-123">Specifies the app settings for the web app as a  Map.</span></span> <span data-ttu-id="64987-124">これらのアプリの設定は、スロットのスワップの間に維持されます。</span><span class="sxs-lookup"><span data-stu-id="64987-124">These app settings will stay at the slot during a swap.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="64987-125">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="64987-125">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>