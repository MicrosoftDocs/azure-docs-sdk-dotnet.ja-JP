<Type Name="IWithTrafficRoutingMethod" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithTrafficRoutingMethod">
  <TypeSignature Language="C#" Value="public interface IWithTrafficRoutingMethod" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTrafficRoutingMethod" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithTrafficRoutingMethod" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTrafficRoutingMethod" />
  <TypeSignature Language="F#" Value="type IWithTrafficRoutingMethod = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="81ed6-101">プロファイルのトラフィック ルーティング方法を指定できるように、トラフィック マネージャー プロファイルの更新の段階です。</span><span class="sxs-lookup"><span data-stu-id="81ed6-101">The stage of the traffic manager profile update allowing to specify the traffic routing method for the profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithGeographicBasedRouting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithGeographicBasedRouting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithGeographicBasedRouting() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithTrafficRoutingMethod.WithGeographicBasedRouting" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGeographicBasedRouting () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithGeographicBasedRouting : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithTrafficRoutingMethod.WithGeographicBasedRouting " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithPerformanceBasedRouting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithPerformanceBasedRouting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithPerformanceBasedRouting() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithTrafficRoutingMethod.WithPerformanceBasedRouting" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPerformanceBasedRouting () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPerformanceBasedRouting : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithTrafficRoutingMethod.WithPerformanceBasedRouting " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="81ed6-102">ユーザーの近くにエンドポイントの地理的な場所に基づきのエンド ユーザー トラフィックがルーティングされることを指定します。</span><span class="sxs-lookup"><span data-stu-id="81ed6-102">Specifies that end user traffic should be routed based on the geographic location of the endpoint close to user.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="81ed6-103">トラフィック マネージャー プロファイルの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="81ed6-103">The next stage of the traffic manager profile update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPriorityBasedRouting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithPriorityBasedRouting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithPriorityBasedRouting() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithTrafficRoutingMethod.WithPriorityBasedRouting" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPriorityBasedRouting () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPriorityBasedRouting : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithTrafficRoutingMethod.WithPriorityBasedRouting " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="81ed6-104">エンド ユーザー トラフィックがつまりその優先順位に基づくエンドポイントにルーティングされることを指定します。 最も高い優先度と最高の優先度のエンドポイントを次に利用可能なフォールバックではない場合、エンドポイントを使用します。</span><span class="sxs-lookup"><span data-stu-id="81ed6-104">Specifies that end user traffic should be routed to the endpoint based on its priority i.e. use the endpoint with highest priority and if it is not available fallback to next highest priority endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="81ed6-105">トラフィック マネージャー プロファイルの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="81ed6-105">The next stage of the traffic manager profile update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithTrafficRoutingMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithTrafficRoutingMethod (Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod routingMethod);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithTrafficRoutingMethod(class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod routingMethod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithTrafficRoutingMethod.WithTrafficRoutingMethod(Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTrafficRoutingMethod (routingMethod As TrafficRoutingMethod) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithTrafficRoutingMethod : Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithTrafficRoutingMethod.WithTrafficRoutingMethod routingMethod" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="routingMethod" Type="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod" />
      </Parameters>
      <Docs>
        <param name="routingMethod"><span data-ttu-id="81ed6-106">プロファイルのトラフィック ルーティング方法。</span><span class="sxs-lookup"><span data-stu-id="81ed6-106">The traffic routing method for the profile.</span></span></param>
        <summary>
            <span data-ttu-id="81ed6-107">プロファイルのトラフィック ルーティング方法を指定します。</span><span class="sxs-lookup"><span data-stu-id="81ed6-107">Specifies the traffic routing method for the profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="81ed6-108">トラフィック マネージャー プロファイルの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="81ed6-108">The next stage of the traffic manager profile update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWeightBasedRouting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithWeightBasedRouting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithWeightBasedRouting() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithTrafficRoutingMethod.WithWeightBasedRouting" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWeightBasedRouting () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithWeightBasedRouting : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithTrafficRoutingMethod.WithWeightBasedRouting " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="81ed6-109">エンド ユーザー トラフィックが、エンドポイントに割り当てられた重みに基づくエンドポイントに分散することを指定します。</span><span class="sxs-lookup"><span data-stu-id="81ed6-109">Specifies that end user traffic should be distributed to the endpoints based on the weight assigned to the endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="81ed6-110">トラフィック マネージャー プロファイルの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="81ed6-110">The next stage of the traffic manager profile update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>