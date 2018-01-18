<Type Name="IWithTtl" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithTtl">
  <TypeSignature Language="C#" Value="public interface IWithTtl" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTtl" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithTtl" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTtl" />
  <TypeSignature Language="F#" Value="type IWithTtl = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d6b55-101">トラフィック マネージャー プロファイルの更新を許可する DNS TTL を指定の段階です。</span><span class="sxs-lookup"><span data-stu-id="d6b55-101">The stage of the traffic manager profile update allowing to specify the DNS TTL.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTimeToLive">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithTimeToLive (int ttlInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithTimeToLive(int32 ttlInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithTtl.WithTimeToLive(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeToLive (ttlInSeconds As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithTimeToLive : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithTtl.WithTimeToLive ttlInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ttlInSeconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="ttlInSeconds"><span data-ttu-id="d6b55-102">DNS の TTL (秒)。</span><span class="sxs-lookup"><span data-stu-id="d6b55-102">DNS TTL in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="d6b55-103">DNS TTL を秒単位で指定します。</span><span class="sxs-lookup"><span data-stu-id="d6b55-103">Specify the DNS TTL in seconds.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d6b55-104">トラフィック マネージャー プロファイルの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="d6b55-104">The next stage of the traffic manager profile update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>