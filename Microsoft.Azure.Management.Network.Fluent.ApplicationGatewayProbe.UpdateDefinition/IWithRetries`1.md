<Type Name="IWithRetries&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithRetries&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithRetries&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRetries`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithRetries`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRetries(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithRetries&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="e4ed8-101">この定義をアタッチした後に戻るには、親アプリケーション ゲートウェイ定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="e4ed8-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="e4ed8-102">サーバーの前に再試行の回数を指定できるようにアプリケーション ゲートウェイ プローブ定義のステージは、異常と見なされます。</span><span class="sxs-lookup"><span data-stu-id="e4ed8-102">Stage of an application gateway probe definition allowing to specify the number of retries before the server is considered unhealthy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRetriesBeforeUnhealthy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithRetriesBeforeUnhealthy (int retryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithRetriesBeforeUnhealthy(int32 retryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithRetries`1.WithRetriesBeforeUnhealthy(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRetriesBeforeUnhealthy (retryCount As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithRetriesBeforeUnhealthy : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithRetries.WithRetriesBeforeUnhealthy retryCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="retryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="retryCount"><span data-ttu-id="e4ed8-103">1 ~ 20 の数値。</span><span class="sxs-lookup"><span data-stu-id="e4ed8-103">A number between 1 and 20.</span></span></param>
        <summary>
            <span data-ttu-id="e4ed8-104">サーバーを異常と見なす前に、再試行の回数を指定します。</span><span class="sxs-lookup"><span data-stu-id="e4ed8-104">Specifies the number of retries before the server is considered unhealthy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e4ed8-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e4ed8-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>