<Type Name="IWithMonitoringConfiguration" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithMonitoringConfiguration">
  <TypeSignature Language="C#" Value="public interface IWithMonitoringConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMonitoringConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithMonitoringConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMonitoringConfiguration" />
  <TypeSignature Language="F#" Value="type IWithMonitoringConfiguration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0968c-101">トラフィック マネージャー プロファイルの更新を許可するエンドポイントの監視構成を指定の段階です。</span><span class="sxs-lookup"><span data-stu-id="0968c-101">The stage of the traffic manager profile update allowing to specify the endpoint monitoring configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithHttpMonitoring">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpMonitoring ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpMonitoring() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithMonitoringConfiguration.WithHttpMonitoring" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpMonitoring () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithHttpMonitoring : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithMonitoringConfiguration.WithHttpMonitoring " />
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
            <span data-ttu-id="0968c-102">HTTP はポート 80 を使用して、定期的に '/'、パスから HTTP 200 の応答を確認するエンドポイントの監視を使用するように指定します。</span><span class="sxs-lookup"><span data-stu-id="0968c-102">Specify to use HTTP monitoring for the endpoints that checks for HTTP 200 response from the path '/' at regular intervals, using port 80.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0968c-103">トラフィック マネージャー プロファイルの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0968c-103">The next stage of the traffic manager profile update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpMonitoring">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpMonitoring (int port, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpMonitoring(int32 port, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithMonitoringConfiguration.WithHttpMonitoring(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpMonitoring (port As Integer, path As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithHttpMonitoring : int * string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithMonitoringConfiguration.WithHttpMonitoring (port, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="port"><span data-ttu-id="0968c-104">監視のポートです。</span><span class="sxs-lookup"><span data-stu-id="0968c-104">The monitoring port.</span></span></param>
        <param name="path"><span data-ttu-id="0968c-105">監視のパス。</span><span class="sxs-lookup"><span data-stu-id="0968c-105">The monitoring path.</span></span></param>
        <summary>
            <span data-ttu-id="0968c-106">一定の間隔で指定されたパスからの HTTP 200 の応答を確認するエンドポイントの監視を指定したポートを使用して、HTTP を指定します。</span><span class="sxs-lookup"><span data-stu-id="0968c-106">Specify the HTTP monitoring for the endpoints that checks for HTTP 200 response from the specified path at regular intervals, using the specified port.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0968c-107">トラフィック マネージャー プロファイルの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0968c-107">The next stage of the traffic manager profile update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpsMonitoring">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpsMonitoring ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpsMonitoring() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithMonitoringConfiguration.WithHttpsMonitoring" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsMonitoring () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsMonitoring : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithMonitoringConfiguration.WithHttpsMonitoring " />
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
            <span data-ttu-id="0968c-108">HTTPS はポート 443 を使用して、定期的に '/'、パスから HTTPS 200 の応答を確認するエンドポイントの監視を使用するように指定します。</span><span class="sxs-lookup"><span data-stu-id="0968c-108">Specify to use HTTPS monitoring for the endpoints that checks for HTTPS 200 response from the path '/' at regular intervals, using port 443.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0968c-109">トラフィック マネージャー プロファイルの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0968c-109">The next stage of the traffic manager profile update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpsMonitoring">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpsMonitoring (int port, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpsMonitoring(int32 port, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithMonitoringConfiguration.WithHttpsMonitoring(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsMonitoring (port As Integer, path As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsMonitoring : int * string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithMonitoringConfiguration.WithHttpsMonitoring (port, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="port"><span data-ttu-id="0968c-110">監視のポートです。</span><span class="sxs-lookup"><span data-stu-id="0968c-110">The monitoring port.</span></span></param>
        <param name="path"><span data-ttu-id="0968c-111">監視のパス。</span><span class="sxs-lookup"><span data-stu-id="0968c-111">The monitoring path.</span></span></param>
        <summary>
            <span data-ttu-id="0968c-112">一定の間隔で指定されたパスからの HTTPS 200 の応答を確認するエンドポイントの監視を指定したポートを使用して、HTTPS を指定します。</span><span class="sxs-lookup"><span data-stu-id="0968c-112">Specify the HTTPS monitoring for the endpoints that checks for HTTPS 200 response from the specified path at regular intervals, using the specified port.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0968c-113">トラフィック マネージャー プロファイルの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0968c-113">The next stage of the traffic manager profile update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>