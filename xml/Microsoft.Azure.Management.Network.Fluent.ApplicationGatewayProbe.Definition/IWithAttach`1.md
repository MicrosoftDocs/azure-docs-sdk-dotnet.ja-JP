<Type Name="IWithAttach&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ReturnT&gt; : Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHealthyHttpResponseBodyContents&lt;ReturnT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHealthyHttpResponseBodyContentsBeta&lt;ReturnT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHealthyHttpResponseStatusCodeRanges&lt;ReturnT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHealthyHttpResponseStatusCodeRangesBeta&lt;ReturnT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithInterval&lt;ReturnT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithRetries&lt;ReturnT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInDefinitionAlt&lt;ReturnT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ReturnT&gt; implements class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHealthyHttpResponseBodyContents`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHealthyHttpResponseBodyContentsBeta`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHealthyHttpResponseStatusCodeRanges`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHealthyHttpResponseStatusCodeRangesBeta`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithInterval`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithRetries`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInDefinitionAlt`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ReturnT)&#xA;Implements IBeta, IInDefinitionAlt(Of ReturnT), IWithHealthyHttpResponseBodyContents(Of ReturnT), IWithHealthyHttpResponseBodyContentsBeta(Of ReturnT), IWithHealthyHttpResponseStatusCodeRanges(Of ReturnT), IWithHealthyHttpResponseStatusCodeRangesBeta(Of ReturnT), IWithInterval(Of ReturnT), IWithRetries(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ReturnT&gt; = interface&#xA;    interface IInDefinitionAlt&lt;'ReturnT&gt;&#xA;    interface IWithInterval&lt;'ReturnT&gt;&#xA;    interface IWithRetries&lt;'ReturnT&gt;&#xA;    interface IWithHealthyHttpResponseStatusCodeRanges&lt;'ReturnT&gt;&#xA;    interface IWithHealthyHttpResponseStatusCodeRangesBeta&lt;'ReturnT&gt;&#xA;    interface IBeta&#xA;    interface IWithHealthyHttpResponseBodyContents&lt;'ReturnT&gt;&#xA;    interface IWithHealthyHttpResponseBodyContentsBeta&lt;'ReturnT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHealthyHttpResponseBodyContents&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHealthyHttpResponseBodyContentsBeta&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHealthyHttpResponseStatusCodeRanges&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHealthyHttpResponseStatusCodeRangesBeta&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithInterval&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithRetries&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInDefinitionAlt&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ReturnT"><span data-ttu-id="a0b62-101">この定義をアタッチした後に戻るには、親アプリケーション ゲートウェイ定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="a0b62-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="a0b62-102">アプリケーション ゲートウェイ プローブ定義の最終段階です。</span><span class="sxs-lookup"><span data-stu-id="a0b62-102">The final stage of an application gateway probe definition.</span></span>
            <span data-ttu-id="a0b62-103">この段階で、残りの省略可能な設定を指定することができます、またはプローブ定義は親アプリケーション ゲートウェイ定義に関連付けることができます。</span><span class="sxs-lookup"><span data-stu-id="a0b62-103">At this stage, any remaining optional settings can be specified, or the probe definition can be attached to the parent application gateway definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>