<Type Name="TelemetryClientExtensions" FullName="Microsoft.ApplicationInsights.TelemetryClientExtensions">
  <TypeSignature Language="C#" Value="public static class TelemetryClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TelemetryClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.TelemetryClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TelemetryClientExtensions" />
  <TypeSignature Language="F#" Value="type TelemetryClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f9011-101">それぞれのフィールドが初期化の操作のオブジェクトを作成する遠隔測定のクライアントに拡張クラス。</span><span class="sxs-lookup"><span data-stu-id="f9011-101">Extension class to telemetry client that creates operation object with the respective fields initialized.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="StartOperation&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt; StartOperation&lt;T&gt; (this Microsoft.ApplicationInsights.TelemetryClient telemetryClient, string operationName) where T : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetrynew();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1&lt;!!T&gt; StartOperation&lt;.ctor (class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry) T&gt;(class Microsoft.ApplicationInsights.TelemetryClient telemetryClient, string operationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation``1(Microsoft.ApplicationInsights.TelemetryClient,System.String)" />
      <MemberSignature Language="F#" Value="static member StartOperation : Microsoft.ApplicationInsights.TelemetryClient * string -&gt; Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry and 'T : (new : unit -&gt; 'T))&gt; (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry and 'T : (new : unit -&gt; 'T))" Usage="Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation (telemetryClient, operationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <BaseTypeName>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="telemetryClient" Type="Microsoft.ApplicationInsights.TelemetryClient" RefType="this" />
        <Parameter Name="operationName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="f9011-102">製品利用統計情報項目の種類。</span><span class="sxs-lookup"><span data-stu-id="f9011-102">Type of the telemetry item.</span></span></typeparam>
        <param name="telemetryClient"><span data-ttu-id="f9011-103">遠隔測定のクライアント オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="f9011-103">Telemetry client object.</span></span></param>
        <param name="operationName"><span data-ttu-id="f9011-104">名前の操作の顧客が反映されるまでを計画します。</span><span class="sxs-lookup"><span data-stu-id="f9011-104">Name of the operation that customer is planning to propagate.</span></span></param>
        <summary>
            <span data-ttu-id="f9011-105">開始操作は、それぞれのテレメトリ項目を操作のオブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="f9011-105">Start operation creates an operation object with a respective telemetry item.</span></span> 
            </summary>
        <returns><span data-ttu-id="f9011-106">操作項目オブジェクトが現在を持つ新しい製品利用統計情報項目では、時間とタイムスタンプを起動します。</span><span class="sxs-lookup"><span data-stu-id="f9011-106">Operation item object with a new telemetry item having current start time and timestamp.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOperation&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt; StartOperation&lt;T&gt; (this Microsoft.ApplicationInsights.TelemetryClient telemetryClient, T operationTelemetry) where T : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1&lt;!!T&gt; StartOperation&lt;(class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry) T&gt;(class Microsoft.ApplicationInsights.TelemetryClient telemetryClient, !!T operationTelemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation``1(Microsoft.ApplicationInsights.TelemetryClient,``0)" />
      <MemberSignature Language="F#" Value="static member StartOperation : Microsoft.ApplicationInsights.TelemetryClient * 'T -&gt; Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)&gt; (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)" Usage="Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation (telemetryClient, operationTelemetry)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="telemetryClient" Type="Microsoft.ApplicationInsights.TelemetryClient" RefType="this" />
        <Parameter Name="operationTelemetry" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="f9011-107">製品利用統計情報項目の種類。</span><span class="sxs-lookup"><span data-stu-id="f9011-107">Type of the telemetry item.</span></span></typeparam>
        <param name="telemetryClient"><span data-ttu-id="f9011-108">遠隔測定のクライアント オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="f9011-108">Telemetry client object.</span></span></param>
        <param name="operationTelemetry"><span data-ttu-id="f9011-109">起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="f9011-109">Operation to start.</span></span></param>
        <summary>
            <span data-ttu-id="f9011-110">特定のテレメトリ項目を操作のオブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="f9011-110">Creates an operation object with a given telemetry item.</span></span> 
            </summary>
        <returns><span data-ttu-id="f9011-111">操作項目オブジェクトが現在を持つ新しい製品利用統計情報項目では、時間とタイムスタンプを起動します。</span><span class="sxs-lookup"><span data-stu-id="f9011-111">Operation item object with a new telemetry item having current start time and timestamp.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOperation&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt; StartOperation&lt;T&gt; (this Microsoft.ApplicationInsights.TelemetryClient telemetryClient, string operationName, string operationId, string parentOperationId = null) where T : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetrynew();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1&lt;!!T&gt; StartOperation&lt;.ctor (class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry) T&gt;(class Microsoft.ApplicationInsights.TelemetryClient telemetryClient, string operationName, string operationId, string parentOperationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation``1(Microsoft.ApplicationInsights.TelemetryClient,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member StartOperation : Microsoft.ApplicationInsights.TelemetryClient * string * string * string -&gt; Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry and 'T : (new : unit -&gt; 'T))&gt; (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry and 'T : (new : unit -&gt; 'T))" Usage="Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation (telemetryClient, operationName, operationId, parentOperationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <BaseTypeName>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="telemetryClient" Type="Microsoft.ApplicationInsights.TelemetryClient" RefType="this" />
        <Parameter Name="operationName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="parentOperationId" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="f9011-112">製品利用統計情報項目の種類。</span><span class="sxs-lookup"><span data-stu-id="f9011-112">Type of the telemetry item.</span></span></typeparam>
        <param name="telemetryClient"><span data-ttu-id="f9011-113">遠隔測定のクライアント オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="f9011-113">Telemetry client object.</span></span></param>
        <param name="operationName"><span data-ttu-id="f9011-114">名前の操作の顧客が反映されるまでを計画します。</span><span class="sxs-lookup"><span data-stu-id="f9011-114">Name of the operation that customer is planning to propagate.</span></span></param>
        <param name="operationId"><span data-ttu-id="f9011-115">新しい操作を設定する操作 ID。</span><span class="sxs-lookup"><span data-stu-id="f9011-115">Operation ID to set in the new operation.</span></span></param>
        <param name="parentOperationId"><span data-ttu-id="f9011-116">新しい操作で設定する省略可能な親操作 ID です。</span><span class="sxs-lookup"><span data-stu-id="f9011-116">Optional parent operation ID to set in the new operation.</span></span></param>
        <summary>
            <span data-ttu-id="f9011-117">開始操作は、それぞれのテレメトリ項目を操作のオブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="f9011-117">Start operation creates an operation object with a respective telemetry item.</span></span> 
            </summary>
        <returns><span data-ttu-id="f9011-118">操作項目オブジェクトが現在を持つ新しい製品利用統計情報項目では、時間とタイムスタンプを起動します。</span><span class="sxs-lookup"><span data-stu-id="f9011-118">Operation item object with a new telemetry item having current start time and timestamp.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopOperation&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static void StopOperation&lt;T&gt; (this Microsoft.ApplicationInsights.TelemetryClient telemetryClient, Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt; operation) where T : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void StopOperation&lt;(class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry) T&gt;(class Microsoft.ApplicationInsights.TelemetryClient telemetryClient, class Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1&lt;!!T&gt; operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClientExtensions.StopOperation``1(Microsoft.ApplicationInsights.TelemetryClient,Microsoft.ApplicationInsights.Extensibility.IOperationHolder{``0})" />
      <MemberSignature Language="F#" Value="static member StopOperation : Microsoft.ApplicationInsights.TelemetryClient * Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)&gt; -&gt; unit (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)" Usage="Microsoft.ApplicationInsights.TelemetryClientExtensions.StopOperation (telemetryClient, operation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="telemetryClient" Type="Microsoft.ApplicationInsights.TelemetryClient" RefType="this" />
        <Parameter Name="operation" Type="Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="telemetryClient"><span data-ttu-id="f9011-119">遠隔測定のクライアント オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="f9011-119">Telemetry client object.</span></span></param>
        <param name="operation"><span data-ttu-id="f9011-120">期間と履歴を計算する操作のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f9011-120">Operation object to compute duration and track.</span></span></param>
        <summary>
            <span data-ttu-id="f9011-121">停止操作は、操作の間を計算し、それぞれの遠隔測定のクライアントを使用してそれを追跡します。</span><span class="sxs-lookup"><span data-stu-id="f9011-121">Stop operation computes the duration of the operation and tracks it using the respective telemetry client.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>