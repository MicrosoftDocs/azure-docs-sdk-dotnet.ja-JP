<Type Name="IWithInstanceCount" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithInstanceCount">
  <TypeSignature Language="C#" Value="public interface IWithInstanceCount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInstanceCount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithInstanceCount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInstanceCount" />
  <TypeSignature Language="F#" Value="type IWithInstanceCount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3bb22-101">アプリケーション ゲートウェイの更新を許可するアプリケーション ゲートウェイの容量 (インスタンスの数) を指定の段階です。</span><span class="sxs-lookup"><span data-stu-id="3bb22-101">The stage of an application gateway update allowing to specify the capacity (number of instances) of the application gateway.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithInstanceCount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithInstanceCount (int instanceCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithInstanceCount(int32 instanceCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithInstanceCount.WithInstanceCount(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithInstanceCount (instanceCount As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithInstanceCount : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithInstanceCount.WithInstanceCount instanceCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instanceCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="instanceCount"><span data-ttu-id="3bb22-102">1 と 10 個が選択されている applicatiob ゲートウェイのサイズの制限に基づくまでの数値として容量。</span><span class="sxs-lookup"><span data-stu-id="3bb22-102">The capacity as a number between 1 and 10 but also based on the limits imposed by the selected applicatiob gateway size.</span></span></param>
        <summary>
            <span data-ttu-id="3bb22-103">アプリケーション ゲートウェイの容量 (インスタンスの数) を指定します。</span><span class="sxs-lookup"><span data-stu-id="3bb22-103">Specifies the capacity (number of instances) for the application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3bb22-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="3bb22-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>