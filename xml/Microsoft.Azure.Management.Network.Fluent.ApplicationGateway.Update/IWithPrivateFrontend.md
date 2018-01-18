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
            <span data-ttu-id="f24b0-101">アプリケーション ゲートウェイをその仮想ネットワークにアクセスできるように許可する内部アプリケーション ゲートウェイの更新プログラムの段階です。</span><span class="sxs-lookup"><span data-stu-id="f24b0-101">The stage of an internal application gateway update allowing to make the application gateway accessible to its virtual network.</span></span>
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
            <span data-ttu-id="f24b0-102">指定をプライベートまたは内部、フロント エンドを有効にするはありません。</span><span class="sxs-lookup"><span data-stu-id="f24b0-102">Specifies that no private, or internal, frontend should be enabled.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f24b0-103">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f24b0-103">The next stage of the definition.</span></span></return>
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
            <span data-ttu-id="f24b0-104">アプリケーション ゲートウェイを含むサブネットのプライベート (内部) の既定のフロント エンドを有効にします。</span><span class="sxs-lookup"><span data-stu-id="f24b0-104">Enables a private (internal) default frontend in the subnet containing the application gateway.</span></span>
            <span data-ttu-id="f24b0-105">必要な場合は、"default"という名前のフロント エンドが作成されます。</span><span class="sxs-lookup"><span data-stu-id="f24b0-105">A frontend with the name "default" will be created if needed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f24b0-106">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f24b0-106">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>