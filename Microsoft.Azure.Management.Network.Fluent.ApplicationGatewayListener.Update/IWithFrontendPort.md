<Type Name="IWithFrontendPort" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontendPort">
  <TypeSignature Language="C#" Value="public interface IWithFrontendPort" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontendPort" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontendPort" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontendPort" />
  <TypeSignature Language="F#" Value="type IWithFrontendPort = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6458e-101">アプリケーション ゲートウェイのフロント エンド リスナーのステージにリスナーを関連付けるには、フロント エンド ポートを指定する許可を更新します。</span><span class="sxs-lookup"><span data-stu-id="6458e-101">The stage of an application gateway frontend listener update allowing to specify the frontend port to associate the listener with.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithFrontendPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithFrontendPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontendPort.WithFrontendPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate" Usage="iWithFrontendPort.WithFrontendPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber"><span data-ttu-id="6458e-102">ポート番号です。</span><span class="sxs-lookup"><span data-stu-id="6458e-102">A port number.</span></span></param>
        <summary>
            <span data-ttu-id="6458e-103">指定したフロント エンド ポート番号でリッスンするリスナーを有効にします。</span><span class="sxs-lookup"><span data-stu-id="6458e-103">Enables the listener to listen on the specified frontend port number.</span></span>
            <span data-ttu-id="6458e-104">このポート番号のフロント エンド ポートがまだ存在しない場合、新しい作成されます自動生成される名前。</span><span class="sxs-lookup"><span data-stu-id="6458e-104">If a frontend port for this port number does not yet exist, a new will be created with an auto-generated name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="6458e-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="6458e-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithFrontendPort (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithFrontendPort(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontendPort.WithFrontendPort(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate" Usage="iWithFrontendPort.WithFrontendPort name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="6458e-106">既存のフロント エンド ポートの名前。</span><span class="sxs-lookup"><span data-stu-id="6458e-106">The name of an existing frontend port.</span></span></param>
        <summary>
            <span data-ttu-id="6458e-107">指定した既存のフロント エンド ポートでリッスンするリスナーを有効にします。</span><span class="sxs-lookup"><span data-stu-id="6458e-107">Enables the listener to listen on the specified existing frontend port.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="6458e-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="6458e-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>