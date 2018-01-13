<Type Name="IWithTrafficRoutingMethod" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod">
  <TypeSignature Language="C#" Value="public interface IWithTrafficRoutingMethod" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTrafficRoutingMethod" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTrafficRoutingMethod" />
  <TypeSignature Language="F#" Value="type IWithTrafficRoutingMethod = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            プロファイルのトラフィック ルーティング方法を指定できるように、トラフィック マネージャー プロファイル定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithGeographicBasedRouting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithGeographicBasedRouting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithGeographicBasedRouting() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod.WithGeographicBasedRouting" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGeographicBasedRouting () As IWithEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithGeographicBasedRouting : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint" Usage="iWithTrafficRoutingMethod.WithGeographicBasedRouting " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithPerformanceBasedRouting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithPerformanceBasedRouting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithPerformanceBasedRouting() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod.WithPerformanceBasedRouting" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPerformanceBasedRouting () As IWithEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithPerformanceBasedRouting : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint" Usage="iWithTrafficRoutingMethod.WithPerformanceBasedRouting " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ユーザーの近くにエンドポイントの地理的な場所に基づきのエンド ユーザー トラフィックがルーティングされることを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPriorityBasedRouting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithPriorityBasedRouting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithPriorityBasedRouting() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod.WithPriorityBasedRouting" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPriorityBasedRouting () As IWithEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithPriorityBasedRouting : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint" Usage="iWithTrafficRoutingMethod.WithPriorityBasedRouting " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            エンド ユーザー トラフィックがつまりその優先順位に基づくエンドポイントにルーティングされることを指定します。 最も高い優先度と最高の優先度のエンドポイントを次に利用可能なフォールバックではない場合、エンドポイントを使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithTrafficRoutingMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithTrafficRoutingMethod (Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod routingMethod);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithTrafficRoutingMethod(class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod routingMethod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod.WithTrafficRoutingMethod(Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTrafficRoutingMethod (routingMethod As TrafficRoutingMethod) As IWithEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithTrafficRoutingMethod : Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint" Usage="iWithTrafficRoutingMethod.WithTrafficRoutingMethod routingMethod" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="routingMethod" Type="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod" />
      </Parameters>
      <Docs>
        <param name="routingMethod">プロファイルのトラフィック ルーティング方法。</param>
        <summary>
            プロファイルのトラフィック ルーティング方法を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithWeightBasedRouting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithWeightBasedRouting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithWeightBasedRouting() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod.WithWeightBasedRouting" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWeightBasedRouting () As IWithEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithWeightBasedRouting : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint" Usage="iWithTrafficRoutingMethod.WithWeightBasedRouting " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            エンド ユーザー トラフィックが、エンドポイントに割り当てられた重みに基づくエンドポイントに分散することを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>