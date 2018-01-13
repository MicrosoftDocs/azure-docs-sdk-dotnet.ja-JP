<Type Name="IProvider" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.IProvider">
  <TypeSignature Language="C#" Value="public interface IProvider : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IProvider implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.IProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IProvider&#xA;Implements IHasInner(Of ProviderInner), IIndexable" />
  <TypeSignature Language="F#" Value="type IProvider = interface&#xA;    interface IIndexable&#xA;    interface IHasInner&lt;ProviderInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="63570-101">Azure リソース プロバイダーの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="63570-101">An immutable client-side representation of an Azure resource provider.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Namespace">
      <MemberSignature Language="C#" Value="public string Namespace { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Namespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IProvider.Namespace" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Namespace As String" />
      <MemberSignature Language="F#" Value="member this.Namespace : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IProvider.Namespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="63570-102">プロバイダーの名前空間</span><span class="sxs-lookup"><span data-stu-id="63570-102">the namespace of the provider</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationState">
      <MemberSignature Language="C#" Value="public string RegistrationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegistrationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IProvider.RegistrationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegistrationState As String" />
      <MemberSignature Language="F#" Value="member this.RegistrationState : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IProvider.RegistrationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="63570-103">示す、プロバイダーの登録状態かどうかこの</span><span class="sxs-lookup"><span data-stu-id="63570-103">the registration state of the provider, indicating whether this</span></span></value>
        <value><span data-ttu-id="63570-104">リソース プロバイダーが現在のサブスクリプションに登録されています。</span><span class="sxs-lookup"><span data-stu-id="63570-104">resource provider is registered in the current subscription</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType&gt; ResourceTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType&gt; ResourceTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IProvider.ResourceTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceTypes As IList(Of ProviderResourceType)" />
      <MemberSignature Language="F#" Value="member this.ResourceTypes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IProvider.ResourceTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="63570-105">プロバイダーの種類のリソースの一覧</span><span class="sxs-lookup"><span data-stu-id="63570-105">the list of provider resource types</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>