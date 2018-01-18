<Type Name="IWithListener" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener">
  <TypeSignature Language="C#" Value="public interface IWithListener" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithListener" />
  <TypeSignature Language="F#" Value="type IWithListener = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cff9a-101">アプリケーション ゲートウェイの更新を許可するフロント エンドのリスナーを変更する段階です。</span><span class="sxs-lookup"><span data-stu-id="cff9a-101">The stage of an application gateway update allowing to modify frontend listeners.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineListener (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineListener(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener.DefineListener(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineListener (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineListener : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithListener.DefineListener name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="cff9a-102">リスナーの一意の名前。</span><span class="sxs-lookup"><span data-stu-id="cff9a-102">A unique name for the listener.</span></span></param>
        <summary>
            <span data-ttu-id="cff9a-103">ゲートウェイに接続する新しいアプリケーション ゲートウェイ リスナーの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="cff9a-103">Begins the definition of a new application gateway listener to be attached to the gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="cff9a-104">リスナーの定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="cff9a-104">The first stage of the listener definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate UpdateListener (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate UpdateListener(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener.UpdateListener(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateListener (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateListener : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate" Usage="iWithListener.UpdateListener name" />
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
        <param name="name"><span data-ttu-id="cff9a-105">更新する既存のリスナーの名前。</span><span class="sxs-lookup"><span data-stu-id="cff9a-105">The name of an existing listener to update.</span></span></param>
        <summary>
            <span data-ttu-id="cff9a-106">リスナーの更新を開始します。</span><span class="sxs-lookup"><span data-stu-id="cff9a-106">Begins the update of a listener.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="cff9a-107">定義または要求されたリスナーが存在しない場合は null の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="cff9a-107">The next stage of the definition or null if the requested listener does not exist.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutListener (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutListener(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener.WithoutListener(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutListener (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutListener : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithListener.WithoutListener name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="cff9a-108">削除するリスナーの名前。</span><span class="sxs-lookup"><span data-stu-id="cff9a-108">The name of the listener to remove.</span></span></param>
        <summary>
            <span data-ttu-id="cff9a-109">アプリケーション ゲートウェイからフロント エンドのリスナーを削除します。</span><span class="sxs-lookup"><span data-stu-id="cff9a-109">Removes a frontend listener from the application gateway.</span></span>
            <span data-ttu-id="cff9a-110">他の設定で参照されているリスナーを削除すると、アプリケーション ゲートウェイが分割することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="cff9a-110">Note that removing a listener referenced by other settings may break the application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="cff9a-111">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="cff9a-111">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>