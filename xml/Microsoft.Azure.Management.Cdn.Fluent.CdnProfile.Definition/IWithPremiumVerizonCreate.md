<Type Name="IWithPremiumVerizonCreate" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreate">
  <TypeSignature Language="C#" Value="public interface IWithPremiumVerizonCreate : Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithCreate, Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreateBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPremiumVerizonCreate implements class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithCreate, class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreateBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPremiumVerizonCreate&#xA;Implements IBeta, ICreatable(Of ICdnProfile), IDefinitionWithTags(Of IWithCreate), IWithCreate, IWithPremiumVerizonCreateBeta" />
  <TypeSignature Language="F#" Value="type IWithPremiumVerizonCreate = interface&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;ICdnProfile&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;&#xA;    interface IWithPremiumVerizonCreateBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithCreate</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreateBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="7cef1-101">作成するリソースの最低限必要な入力すべてにはが含まれていますが、指定する省略可能なその他の設定もできる定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="7cef1-101">The stage of the definition which contains all the minimum required inputs for the resource to be created but also allows for any other optional settings to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewPremiumEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.PremiumEndpoint.IPremiumEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreate&gt; DefineNewPremiumEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.PremiumEndpoint.IPremiumEndpoint`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreate&gt; DefineNewPremiumEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreate.DefineNewPremiumEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewPremiumEndpoint (name As String) As IPremiumEndpoint(Of IWithPremiumVerizonCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewPremiumEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.PremiumEndpoint.IPremiumEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreate&gt;" Usage="iWithPremiumVerizonCreate.DefineNewPremiumEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.PremiumEndpoint.IPremiumEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7cef1-102">エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="7cef1-102">A name for the endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="7cef1-103">CDN プロファイルに接続する新しいエンドポイントの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="7cef1-103">Starts the definition of a new endpoint to be attached to the CDN profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7cef1-104">新しい CDN エンドポイントの定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="7cef1-104">The first stage of a new CDN endpoint definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPremiumEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreate WithNewPremiumEndpoint (string endpointOriginHostname);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreate WithNewPremiumEndpoint(string endpointOriginHostname) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreate.WithNewPremiumEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPremiumEndpoint (endpointOriginHostname As String) As IWithPremiumVerizonCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPremiumEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreate" Usage="iWithPremiumVerizonCreate.WithNewPremiumEndpoint endpointOriginHostname" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithPremiumVerizonCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointOriginHostname" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointOriginHostname"><span data-ttu-id="7cef1-105">エンドポイント配信元ホスト名です。</span><span class="sxs-lookup"><span data-stu-id="7cef1-105">An endpoint origin hostname.</span></span></param>
        <summary>
            <span data-ttu-id="7cef1-106">現在の CDN プロファイルを新しいエンドポイントを追加します。</span><span class="sxs-lookup"><span data-stu-id="7cef1-106">Adds a new endpoint to current CDN profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7cef1-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="7cef1-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>