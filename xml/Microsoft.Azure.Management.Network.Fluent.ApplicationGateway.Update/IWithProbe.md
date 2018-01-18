<Type Name="IWithProbe" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithProbe">
  <TypeSignature Language="C#" Value="public interface IWithProbe" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithProbe" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithProbe" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithProbe" />
  <TypeSignature Language="F#" Value="type IWithProbe = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c9937-101">アプリケーション ゲートウェイの更新を許可するプローブの変更の段階です。</span><span class="sxs-lookup"><span data-stu-id="c9937-101">The stage of an application gateway update allowing to modify probes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineProbe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineProbe (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineProbe(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithProbe.DefineProbe(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineProbe (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineProbe : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithProbe.DefineProbe name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c9937-102">プローブの一意の名前。</span><span class="sxs-lookup"><span data-stu-id="c9937-102">A unique name for the probe.</span></span></param>
        <summary>
            <span data-ttu-id="c9937-103">新しいプローブの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="c9937-103">Begins the definition of a new probe.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c9937-104">プローブの定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="c9937-104">The first stage of a probe definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateProbe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate UpdateProbe (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate UpdateProbe(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithProbe.UpdateProbe(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateProbe (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateProbe : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate" Usage="iWithProbe.UpdateProbe name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c9937-105">既存のプローブの名前。</span><span class="sxs-lookup"><span data-stu-id="c9937-105">The name of an existing probe.</span></span></param>
        <summary>
            <span data-ttu-id="c9937-106">既存のプローブの更新を開始します。</span><span class="sxs-lookup"><span data-stu-id="c9937-106">Begins the update of an existing probe.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c9937-107">プローブの更新の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="c9937-107">The first stage of a probe update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutProbe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutProbe (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutProbe(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithProbe.WithoutProbe(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutProbe (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutProbe : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithProbe.WithoutProbe name" />
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
        <param name="name"><span data-ttu-id="c9937-108">既存のプローブの名前。</span><span class="sxs-lookup"><span data-stu-id="c9937-108">The name of an existing probe.</span></span></param>
        <summary>
            <span data-ttu-id="c9937-109">アプリケーション ゲートウェイからプローブを削除します。</span><span class="sxs-lookup"><span data-stu-id="c9937-109">Removes a probe from the application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c9937-110">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c9937-110">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>