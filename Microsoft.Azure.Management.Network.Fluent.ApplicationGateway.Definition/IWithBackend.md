<Type Name="IWithBackend" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithBackend">
  <TypeSignature Language="C#" Value="public interface IWithBackend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithBackend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackend" />
  <TypeSignature Language="F#" Value="type IWithBackend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0d725-101">バックエンドの追加を許可するアプリケーション ゲートウェイ定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="0d725-101">The stage of an application gateway definition allowing to add a backend.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt; DefineBackend (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt; DefineBackend(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithBackend.DefineBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineBackend (name As String) As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;" Usage="iWithBackend.DefineBackend name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="0d725-102">バックエンドの一意の名前。</span><span class="sxs-lookup"><span data-stu-id="0d725-102">A unique name for the backend.</span></span></param>
        <summary>
            <span data-ttu-id="0d725-103">ゲートウェイに接続する新しいアプリケーション ゲートウェイのバックエンドの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="0d725-103">Begins the definition of a new application gateway backend to be attached to the gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0d725-104">バックエンドの定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="0d725-104">The first stage of the backend definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>