<Type Name="IWithEndpoint" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint">
  <TypeSignature Language="C#" Value="public interface IWithEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithEndpoint" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithEndpoint" />
  <TypeSignature Language="F#" Value="type IWithEndpoint = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7207f-101">エンドポイントを指定できるように、トラフィック マネージャー プロファイル定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="7207f-101">The stage of the traffic manager profile definition allowing to specify endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineAzureTargetEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IAzureTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt; DefineAzureTargetEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IAzureTargetEndpointBlank`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt; DefineAzureTargetEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint.DefineAzureTargetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineAzureTargetEndpoint (name As String) As IAzureTargetEndpointBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineAzureTargetEndpoint : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IAzureTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt;" Usage="iWithEndpoint.DefineAzureTargetEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IAzureTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7207f-102">エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="7207f-102">The name for the endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="7207f-103">Azure traffic manager プロファイルにアタッチされているエンドポイントの定義を指定します。</span><span class="sxs-lookup"><span data-stu-id="7207f-103">Specifies definition of an Azure endpoint to be attached to the traffic manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7207f-104">エンドポイントの構成を表す段階です。</span><span class="sxs-lookup"><span data-stu-id="7207f-104">The stage representing configuration for the endpoint.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefineExternalTargetEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IExternalTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt; DefineExternalTargetEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IExternalTargetEndpointBlank`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt; DefineExternalTargetEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint.DefineExternalTargetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineExternalTargetEndpoint (name As String) As IExternalTargetEndpointBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineExternalTargetEndpoint : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IExternalTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt;" Usage="iWithEndpoint.DefineExternalTargetEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IExternalTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7207f-105">エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="7207f-105">The name for the endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="7207f-106">Traffic manager プロファイルにアタッチされている外部エンドポイントの定義を指定します。</span><span class="sxs-lookup"><span data-stu-id="7207f-106">Specifies definition of an external endpoint to be attached to the traffic manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7207f-107">エンドポイントの構成を表す段階です。</span><span class="sxs-lookup"><span data-stu-id="7207f-107">The stage representing configuration for the endpoint.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefineNestedTargetEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.INestedProfileTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt; DefineNestedTargetEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.INestedProfileTargetEndpointBlank`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt; DefineNestedTargetEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint.DefineNestedTargetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNestedTargetEndpoint (name As String) As INestedProfileTargetEndpointBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNestedTargetEndpoint : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.INestedProfileTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt;" Usage="iWithEndpoint.DefineNestedTargetEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.INestedProfileTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7207f-108">エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="7207f-108">The name for the endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="7207f-109">Traffic manager プロファイルにアタッチされている入れ子になったプロファイル エンドポイントの定義を指定します。</span><span class="sxs-lookup"><span data-stu-id="7207f-109">Specifies definition of an nested profile endpoint to be attached to the traffic manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7207f-110">エンドポイントの構成を表す段階です。</span><span class="sxs-lookup"><span data-stu-id="7207f-110">The stage representing configuration for the endpoint.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>