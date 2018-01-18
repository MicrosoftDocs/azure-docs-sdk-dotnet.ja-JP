<Type Name="IWithNestedProfileConfig" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithNestedProfileConfig">
  <TypeSignature Language="C#" Value="public interface IWithNestedProfileConfig" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNestedProfileConfig" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithNestedProfileConfig" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNestedProfileConfig" />
  <TypeSignature Language="F#" Value="type IWithNestedProfileConfig = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1bf6d-101">入れ子になったプロファイル エンドポイントのステージでは、プロファイルと最小の子エンドポイントを指定する許可を更新します。</span><span class="sxs-lookup"><span data-stu-id="1bf6d-101">The stage of an nested profile endpoint update allowing to specify profile and minimum child endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint ToProfile (Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile nestedProfile);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint ToProfile(class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile nestedProfile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithNestedProfileConfig.ToProfile(Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToProfile (nestedProfile As ITrafficManagerProfile) As IUpdateNestedProfileEndpoint" />
      <MemberSignature Language="F#" Value="abstract member ToProfile : Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint" Usage="iWithNestedProfileConfig.ToProfile nestedProfile" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nestedProfile" Type="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile" />
      </Parameters>
      <Docs>
        <param name="nestedProfile"><span data-ttu-id="1bf6d-102">入れ子になった traffic manager プロファイルでします。</span><span class="sxs-lookup"><span data-stu-id="1bf6d-102">The nested traffic manager profile.</span></span></param>
        <summary>
            <span data-ttu-id="1bf6d-103">エンドポイントの入れ子になった traffic manager プロファイルを指定します。</span><span class="sxs-lookup"><span data-stu-id="1bf6d-103">Specifies a nested traffic manager profile for the endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1bf6d-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="1bf6d-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithMinimumEndpointsToEnableTraffic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint WithMinimumEndpointsToEnableTraffic (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint WithMinimumEndpointsToEnableTraffic(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithNestedProfileConfig.WithMinimumEndpointsToEnableTraffic(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMinimumEndpointsToEnableTraffic (count As Integer) As IUpdateNestedProfileEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithMinimumEndpointsToEnableTraffic : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint" Usage="iWithNestedProfileConfig.WithMinimumEndpointsToEnableTraffic count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count"><span data-ttu-id="1bf6d-105">エンドポイントの数。</span><span class="sxs-lookup"><span data-stu-id="1bf6d-105">Number of endpoints.</span></span></param>
        <summary>
            <span data-ttu-id="1bf6d-106">正常と見なされるには、入れ子になったプロファイルをオンラインにするエンドポイントの最小数を指定します。</span><span class="sxs-lookup"><span data-stu-id="1bf6d-106">Specifies the minimum number of endpoints to be online for the nested profile to be considered healthy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1bf6d-107">エンドポイントの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="1bf6d-107">The next stage of the endpoint update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>