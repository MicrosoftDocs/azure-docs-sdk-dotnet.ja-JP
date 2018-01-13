<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInUpdate(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInUpdate&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">WithAttach.attach() の戻り値の型。</typeparam>
    <summary>
            セキュリティ ルールの定義の最終段階です。
            この段階で、残りの省略可能な設定を指定することができます、またはセキュリティ ルールの定義は、親ネットワーク セキュリティ グループを使用して定義 WithAttach.attach() に関連付けることができます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDescription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithDescription (string descrtiption);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithDescription(string descrtiption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach`1.WithDescription(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDescription (descrtiption As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDescription : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAttach.WithDescription descrtiption" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="descrtiption" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="descrtiption">セキュリティの規則に関連付けるテキストの説明です。</param>
        <summary>
            このセキュリティの規則の説明を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPriority">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithPriority (int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithPriority(int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach`1.WithPriority(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPriority (priority As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPriority : int -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAttach.WithPriority priority" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="priority">100 ~ 4096 の範囲の優先度の数です。</param>
        <summary>
            このルールに割り当てる優先度を指定します。
            セキュリティ ルールは、割り当てられた優先度の順序で適用されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>