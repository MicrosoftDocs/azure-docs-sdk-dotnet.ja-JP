<Type Name="IWithTimeout&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithTimeout&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTimeout`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTimeout(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithTimeout&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="61e24-101">この定義をアタッチした後に戻るには、親アプリケーション ゲートウェイ定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="61e24-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="61e24-102">アプリケーション ゲートウェイ プローブ定義できるようにする、プローブと考えられる after の時間を指定の段階が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="61e24-102">Stage of an application gateway probe definition allowing to specify the amount of time to after which the probe is considered failed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach&lt;ParentT&gt; WithTimeoutInSeconds (int seconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach`1&lt;!ParentT&gt; WithTimeoutInSeconds(int32 seconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout`1.WithTimeoutInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeoutInSeconds (seconds As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTimeoutInSeconds : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithTimeout.WithTimeoutInSeconds seconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="seconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="seconds"><span data-ttu-id="61e24-103">1 ~ 86400 の範囲の秒数です。</span><span class="sxs-lookup"><span data-stu-id="61e24-103">A number of seconds, between 1 and 86400.</span></span></param>
        <summary>
            <span data-ttu-id="61e24-104">プローブと見なされるまで、応答の待機に失敗しました (秒) の時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="61e24-104">Specifies the amount of time in seconds waiting for a response before the probe is considered failed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="61e24-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="61e24-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>