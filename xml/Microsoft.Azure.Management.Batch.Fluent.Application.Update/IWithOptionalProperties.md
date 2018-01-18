<Type Name="IWithOptionalProperties" FullName="Microsoft.Azure.Management.Batch.Fluent.Application.Update.IWithOptionalProperties">
  <TypeSignature Language="C#" Value="public interface IWithOptionalProperties" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOptionalProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Application.Update.IWithOptionalProperties" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOptionalProperties" />
  <TypeSignature Language="F#" Value="type IWithOptionalProperties = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c670c-101">アプリケーションのステージを更新を有効にするにまたはアプリケーションの自動アップグレードを無効にできるようにします。</span><span class="sxs-lookup"><span data-stu-id="c670c-101">The stage of an application update allowing to enable or disable auto upgrade of the application.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAllowUpdates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate WithAllowUpdates (bool allowUpdates);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate WithAllowUpdates(bool allowUpdates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Application.Update.IWithOptionalProperties.WithAllowUpdates(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAllowUpdates (allowUpdates As Boolean) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithAllowUpdates : bool -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate" Usage="iWithOptionalProperties.WithAllowUpdates allowUpdates" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="allowUpdates" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="allowUpdates"><span data-ttu-id="c670c-102">できる場合は true、アプリケーションの自動更新それ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="c670c-102">True to allow the automatic updates of the application, otherwise false.</span></span></param>
        <summary>
            <span data-ttu-id="c670c-103">アプリケーションの自動更新をできます。</span><span class="sxs-lookup"><span data-stu-id="c670c-103">Allows automatic application updates.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c670c-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c670c-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithDisplayName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate WithDisplayName (string displayName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate WithDisplayName(string displayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Application.Update.IWithOptionalProperties.WithDisplayName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDisplayName (displayName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDisplayName : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate" Usage="iWithOptionalProperties.WithDisplayName displayName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="displayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="displayName"><span data-ttu-id="c670c-105">表示名。</span><span class="sxs-lookup"><span data-stu-id="c670c-105">A display name.</span></span></param>
        <summary>
            <span data-ttu-id="c670c-106">アプリケーションの表示名を指定します。</span><span class="sxs-lookup"><span data-stu-id="c670c-106">Specifies the display name for the application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c670c-107">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c670c-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>