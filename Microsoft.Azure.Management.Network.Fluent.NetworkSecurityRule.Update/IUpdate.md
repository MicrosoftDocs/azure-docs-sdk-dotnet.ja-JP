<Type Name="IUpdate" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate">
  <TypeSignature Language="C#" Value="public interface IUpdate : Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationAddress, Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationPort, Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDirectionAccess, Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithProtocol, Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourceAddress, Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourcePort, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.ISettable&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IUpdate implements class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationAddress, class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationPort, class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDirectionAccess, class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithProtocol, class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourceAddress, class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourcePort, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.ISettable`1&lt;class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IUpdate&#xA;Implements ISettable(Of IUpdate), IWithDestinationAddress, IWithDestinationPort, IWithDirectionAccess, IWithProtocol, IWithSourceAddress, IWithSourcePort" />
  <TypeSignature Language="F#" Value="type IUpdate = interface&#xA;    interface IWithDirectionAccess&#xA;    interface IWithSourceAddress&#xA;    interface IWithSourcePort&#xA;    interface IWithDestinationAddress&#xA;    interface IWithDestinationPort&#xA;    interface IWithProtocol&#xA;    interface ISettable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationAddress</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationPort</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDirectionAccess</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithProtocol</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourceAddress</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourcePort</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.ISettable&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            ネットワーク セキュリティ グループの更新の一部としてセキュリティ ルールの更新の全体です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDescription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate WithDescription (string description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate WithDescription(string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate.WithDescription(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDescription (description As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDescription : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iUpdate.WithDescription description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="description">このセキュリティの規則に関連付けるテキストの説明です。</param>
        <summary>
            このセキュリティの規則の説明を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPriority">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate WithPriority (int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate WithPriority(int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate.WithPriority(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPriority (priority As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPriority : int -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iUpdate.WithPriority priority" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="priority">100 ~ 4096 の範囲の優先度の数です。</param>
        <summary>
            このセキュリティの規則に割り当てる優先度を指定します。
            セキュリティ ルールは、割り当てられた優先度の順序で適用されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>