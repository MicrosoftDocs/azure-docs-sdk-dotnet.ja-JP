<Type Name="IWithFrontendPort" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithFrontendPort">
  <TypeSignature Language="C#" Value="public interface IWithFrontendPort" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontendPort" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithFrontendPort" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontendPort" />
  <TypeSignature Language="F#" Value="type IWithFrontendPort = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6cbf3-101">フロント エンド ポートの追加を許可するアプリケーション ゲートウェイ定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="6cbf3-101">The stage of an application gateway definition allowing to add a frontend port.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithFrontendPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithFrontendPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithFrontendPort.WithFrontendPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate" Usage="iWithFrontendPort.WithFrontendPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber"><span data-ttu-id="6cbf3-102">ポート番号です。</span><span class="sxs-lookup"><span data-stu-id="6cbf3-102">A port number.</span></span></param>
        <summary>
            <span data-ttu-id="6cbf3-103">既に存在しない限り、自動生成の名前と、指定したポート番号、フロント エンド ポートを作成します。</span><span class="sxs-lookup"><span data-stu-id="6cbf3-103">Creates a frontend port with an auto-generated name and the specified port number, unless one already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="6cbf3-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="6cbf3-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithFrontendPort (int portNumber, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithFrontendPort(int32 portNumber, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithFrontendPort.WithFrontendPort(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer, name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int * string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate" Usage="iWithFrontendPort.WithFrontendPort (portNumber, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="portNumber"><span data-ttu-id="6cbf3-105">ポート番号です。</span><span class="sxs-lookup"><span data-stu-id="6cbf3-105">A port number.</span></span></param>
        <param name="name"><span data-ttu-id="6cbf3-106">ポートに割り当てる名前。</span><span class="sxs-lookup"><span data-stu-id="6cbf3-106">The name to assign to the port.</span></span></param>
        <summary>
            <span data-ttu-id="6cbf3-107">既にこの名前、および数に一致するポートが存在しない場合は、指定した名前とポート番号をフロント エンド ポートを作成します。</span><span class="sxs-lookup"><span data-stu-id="6cbf3-107">Creates a frontend port with the specified name and port number, unless a port matching this name and/or number already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="6cbf3-108">次のステージの定義、または null の場合は、名前と、番号の両方ではなくはどちらかに一致するポートは既に存在します。</span><span class="sxs-lookup"><span data-stu-id="6cbf3-108">The next stage of the definition, or null if a port matching either the name or the number, but not both, already exists.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>