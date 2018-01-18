<Type Name="JobStreamListParameters" FullName="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters">
  <TypeSignature Language="C#" Value="public class JobStreamListParameters : Microsoft.Azure.Management.Automation.Models.ParametersWithSkipToken" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobStreamListParameters extends Microsoft.Azure.Management.Automation.Models.ParametersWithSkipToken" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.JobStreamListParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class JobStreamListParameters&#xA;Inherits ParametersWithSkipToken" />
  <TypeSignature Language="F#" Value="type JobStreamListParameters = class&#xA;    inherit ParametersWithSkipToken" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Automation.Models.ParametersWithSkipToken</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="44a3f-101">リスト ジョブ ストリームのストリームの項目の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="44a3f-101">The parameters supplied to the list job stream's stream items operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStreamListParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.JobStreamListParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="44a3f-102">JobStreamListParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="44a3f-102">Initializes a new instance of the JobStreamListParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StreamType">
      <MemberSignature Language="C#" Value="public string StreamType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StreamType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobStreamListParameters.StreamType" />
      <MemberSignature Language="VB.NET" Value="Public Property StreamType As String" />
      <MemberSignature Language="F#" Value="member this.StreamType : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters.StreamType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44a3f-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="44a3f-103">Optional.</span></span> <span data-ttu-id="44a3f-104">ジョブ ストリームの種類。</span><span class="sxs-lookup"><span data-stu-id="44a3f-104">The type of the job stream.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Time">
      <MemberSignature Language="C#" Value="public string Time { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Time" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobStreamListParameters.Time" />
      <MemberSignature Language="VB.NET" Value="Public Property Time As String" />
      <MemberSignature Language="F#" Value="member this.Time : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters.Time" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44a3f-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="44a3f-105">Optional.</span></span> <span data-ttu-id="44a3f-106">時間フィルターを使用すると、この時刻より後に作成されたストリーム レコードを取得できます。</span><span class="sxs-lookup"><span data-stu-id="44a3f-106">Use the time filter to retrieve stream records created after this time.</span></span> <span data-ttu-id="44a3f-107">値は、datetime 形式の文字列に UTC ISO 8601 形式で定義されているようにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="44a3f-107">The value should be a datetime string in UTC format as defined in ISO 8601.</span></span> <span data-ttu-id="44a3f-108">たとえば、2014-09-25T17:49:17.2252204Z</span><span class="sxs-lookup"><span data-stu-id="44a3f-108">For example, 2014-09-25T17:49:17.2252204Z</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>