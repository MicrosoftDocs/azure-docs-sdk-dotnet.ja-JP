<Type Name="IWithRetries" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithRetries">
  <TypeSignature Language="C#" Value="public interface IWithRetries" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRetries" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithRetries" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRetries" />
  <TypeSignature Language="F#" Value="type IWithRetries = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="65464-101">アプリケーション ゲートウェイ プローブ更新できるようにするサーバーを異常と見なす前に、再試行の回数を指定の段階です。</span><span class="sxs-lookup"><span data-stu-id="65464-101">Stage of an application gateway probe update allowing to specify the number of retries before the server is considered unhealthy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRetriesBeforeUnhealthy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate WithRetriesBeforeUnhealthy (int retryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate WithRetriesBeforeUnhealthy(int32 retryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithRetries.WithRetriesBeforeUnhealthy(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRetriesBeforeUnhealthy (retryCount As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithRetriesBeforeUnhealthy : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate" Usage="iWithRetries.WithRetriesBeforeUnhealthy retryCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="retryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="retryCount"><span data-ttu-id="65464-102">1 ~ 20 の数値。</span><span class="sxs-lookup"><span data-stu-id="65464-102">A number between 1 and 20.</span></span></param>
        <summary>
            <span data-ttu-id="65464-103">サーバーを異常と見なす前に、再試行の回数を指定します。</span><span class="sxs-lookup"><span data-stu-id="65464-103">Specifies the number of retries before the server is considered unhealthy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="65464-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="65464-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>