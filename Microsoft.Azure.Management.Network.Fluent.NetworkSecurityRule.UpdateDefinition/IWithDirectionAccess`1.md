<Type Name="IWithDirectionAccess&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithDirectionAccess&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDirectionAccess&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDirectionAccess`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithDirectionAccess`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDirectionAccess(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithDirectionAccess&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るに親の定義の段階です。</typeparam>
    <summary>
            方向のアプリケーションとアクセスの種類を指定するネットワーク規則の説明の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllowInbound">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress&lt;ParentT&gt; AllowInbound ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress`1&lt;!ParentT&gt; AllowInbound() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithDirectionAccess`1.AllowInbound" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowInbound () As IWithSourceAddress(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member AllowInbound : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress&lt;'ParentT&gt;" Usage="iWithDirectionAccess.AllowInbound " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            受信トラフィックを許可します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="AllowOutbound">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress&lt;ParentT&gt; AllowOutbound ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress`1&lt;!ParentT&gt; AllowOutbound() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithDirectionAccess`1.AllowOutbound" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowOutbound () As IWithSourceAddress(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member AllowOutbound : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress&lt;'ParentT&gt;" Usage="iWithDirectionAccess.AllowOutbound " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            送信トラフィックを許可します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="DenyInbound">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress&lt;ParentT&gt; DenyInbound ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress`1&lt;!ParentT&gt; DenyInbound() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithDirectionAccess`1.DenyInbound" />
      <MemberSignature Language="VB.NET" Value="Public Function DenyInbound () As IWithSourceAddress(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member DenyInbound : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress&lt;'ParentT&gt;" Usage="iWithDirectionAccess.DenyInbound " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            受信トラフィックをブロックします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="DenyOutbound">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress&lt;ParentT&gt; DenyOutbound ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress`1&lt;!ParentT&gt; DenyOutbound() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithDirectionAccess`1.DenyOutbound" />
      <MemberSignature Language="VB.NET" Value="Public Function DenyOutbound () As IWithSourceAddress(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member DenyOutbound : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress&lt;'ParentT&gt;" Usage="iWithDirectionAccess.DenyOutbound " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithSourceAddress&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            送信トラフィックをブロックします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>