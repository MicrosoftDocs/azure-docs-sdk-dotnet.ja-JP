<Type Name="IWithPrivateFrontend" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithPrivateFrontend">
  <TypeSignature Language="C#" Value="public interface IWithPrivateFrontend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrivateFrontend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithPrivateFrontend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrivateFrontend" />
  <TypeSignature Language="F#" Value="type IWithPrivateFrontend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            アプリケーション ゲートウェイをその仮想ネットワークにアクセスできるように許可する内部アプリケーション ゲートウェイの更新プログラムの段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithPrivateFrontend.WithoutPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrivateFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithPrivateFrontend.WithoutPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            指定をプライベートまたは内部、フロント エンドを有効にするはありません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithPrivateFrontend.WithPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithPrivateFrontend.WithPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            アプリケーション ゲートウェイを含むサブネットのプライベート (内部) の既定のフロント エンドを有効にします。
            必要な場合は、"default"という名前のフロント エンドが作成されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>