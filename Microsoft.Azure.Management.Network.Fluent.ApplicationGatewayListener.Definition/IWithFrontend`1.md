<Type Name="IWithFrontend&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontend&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFrontend&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontend`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontend`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontend(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithFrontend&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るには、親アプリケーション ゲートウェイ定義の段階です。</typeparam>
    <summary>
            関連付けるリスナーが、フロント エンド IP 構成を指定できるようにアプリケーション ゲートウェイ フロント エンド リスナー定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort&lt;ParentT&gt; WithPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort`1&lt;!ParentT&gt; WithPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontend`1.WithPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateFrontend () As IWithFrontendPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort&lt;'ParentT&gt;" Usage="iWithFrontend.WithPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            アプリケーション ゲートウェイのプライベート (内部) フロント エンド、リスナーに関連付けます。
            プライベート フロント エンドがまだ存在しない場合、自動生成された名前の下に作成およびアプリケーション ゲートウェイのサブネットに関連付けられたするされます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort&lt;ParentT&gt; WithPublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort`1&lt;!ParentT&gt; WithPublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontend`1.WithPublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicFrontend () As IWithFrontendPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort&lt;'ParentT&gt;" Usage="iWithFrontend.WithPublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            アプリケーション ゲートウェイのパブリック (インターネット側) フロント エンド、リスナーに関連付けます。
            パブリック フロント エンドがまだ存在しない場合、自動生成された名前の下に作成およびアプリケーション ゲートウェイのパブリック IP アドレスに関連付けられているされます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>