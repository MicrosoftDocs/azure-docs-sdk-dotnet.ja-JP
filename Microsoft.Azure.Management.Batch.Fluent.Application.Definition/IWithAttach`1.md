<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithApplicationPackage&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithApplicationPackage`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInDefinition(Of ParentT), IWithApplicationPackage(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInDefinition&lt;'ParentT&gt;&#xA;    interface IWithApplicationPackage&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithApplicationPackage&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るには、親バッチ アカウント定義の段階です。</typeparam>
    <summary>
            アプリケーション定義の最終段階です。
            この段階で、残りの省略可能な設定を指定することができます、またはアプリケーション定義は、親のバッチ アカウントの定義に関連付けることができます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAllowUpdates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;ParentT&gt; WithAllowUpdates (bool allowUpdates);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach`1&lt;!ParentT&gt; WithAllowUpdates(bool allowUpdates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach`1.WithAllowUpdates(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAllowUpdates (allowUpdates As Boolean) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAllowUpdates : bool -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAttach.WithAllowUpdates allowUpdates" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="allowUpdates" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="allowUpdates">できる場合は true、アプリケーションの自動更新それ以外の場合は false。</param>
        <summary>
            アプリケーションの自動更新を許可するバッチ アプリケーション定義の段階です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithDisplayName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;ParentT&gt; WithDisplayName (string displayName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach`1&lt;!ParentT&gt; WithDisplayName(string displayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach`1.WithDisplayName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDisplayName (displayName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDisplayName : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAttach.WithDisplayName displayName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="displayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="displayName">表示名。</param>
        <summary>
            バッチのアプリケーションの表示名を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>