<Type Name="OperationTelemetryExtensions" FullName="Microsoft.ApplicationInsights.OperationTelemetryExtensions">
  <TypeSignature Language="C#" Value="public static class OperationTelemetryExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OperationTelemetryExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.OperationTelemetryExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OperationTelemetryExtensions" />
  <TypeSignature Language="F#" Value="type OperationTelemetryExtensions = class" />
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
            <span data-ttu-id="4e796-101">起動し、タイマーを停止する操作テレメトリする拡張関数。</span><span class="sxs-lookup"><span data-stu-id="4e796-101">Extension functions to operation telemetry that start and stop the timer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GenerateOperationId">
      <MemberSignature Language="C#" Value="public static void GenerateOperationId (this Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void GenerateOperationId(class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.OperationTelemetryExtensions.GenerateOperationId(Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub GenerateOperationId (telemetry As OperationTelemetry)" />
      <MemberSignature Language="F#" Value="static member GenerateOperationId : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry -&gt; unit" Usage="Microsoft.ApplicationInsights.OperationTelemetryExtensions.GenerateOperationId telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry" RefType="this" />
      </Parameters>
      <Docs>
        <param name="telemetry"><span data-ttu-id="4e796-102">操作 id を初期化するために遠隔測定します。</span><span class="sxs-lookup"><span data-stu-id="4e796-102">Telemetry to initialize Operation id for.</span></span></param>
        <summary>
            <span data-ttu-id="4e796-103">ランダムな操作 Id を生成し、OperationContext に設定します。</span><span class="sxs-lookup"><span data-stu-id="4e796-103">Generate random operation Id and set it to OperationContext.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static void Start (this Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Start(class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.OperationTelemetryExtensions.Start(Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Start (telemetry As OperationTelemetry)" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry -&gt; unit" Usage="Microsoft.ApplicationInsights.OperationTelemetryExtensions.Start telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry" RefType="this" />
      </Parameters>
      <Docs>
        <param name="telemetry"><span data-ttu-id="4e796-104">この拡張メソッドを呼び出すのテレメトリ項目オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4e796-104">Telemetry item object that calls this extension method.</span></span></param>
        <summary>
            <span data-ttu-id="4e796-105">拡張機能のタイマーを開始する製品利用統計情報項目に、それぞれの製品利用統計情報。</span><span class="sxs-lookup"><span data-stu-id="4e796-105">An extension to telemetry item that starts the timer for the the respective telemetry.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static void Start (this Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry telemetry, long timestamp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Start(class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry telemetry, int64 timestamp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.OperationTelemetryExtensions.Start(Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Start (telemetry As OperationTelemetry, timestamp As Long)" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry * int64 -&gt; unit" Usage="Microsoft.ApplicationInsights.OperationTelemetryExtensions.Start (telemetry, timestamp)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry" RefType="this" />
        <Parameter Name="timestamp" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="telemetry"><span data-ttu-id="4e796-106">この拡張メソッドを呼び出すのテレメトリ項目オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4e796-106">Telemetry item object that calls this extension method.</span></span></param>
        <param name="timestamp"><span data-ttu-id="4e796-107">高解像度のタイムスタンプから<see cref="T:System.Diagnostics.Stopwatch" />です。</span><span class="sxs-lookup"><span data-stu-id="4e796-107">A high-resolution timestamp from <see cref="T:System.Diagnostics.Stopwatch" />.</span></span></param>
        <summary>
            <span data-ttu-id="4e796-108">タイマーを初期化する製品利用統計情報項目の拡張機能は、高解像度のタイムスタンプを使用してそれぞれの遠隔測定<see cref="T:System.Diagnostics.Stopwatch" />です。</span><span class="sxs-lookup"><span data-stu-id="4e796-108">An extension to telemetry item that initializes the timer for the the respective telemetry using a timestamp from a high-resolution <see cref="T:System.Diagnostics.Stopwatch" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static void Stop (this Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Stop(class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.OperationTelemetryExtensions.Stop(Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Stop (telemetry As OperationTelemetry)" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry -&gt; unit" Usage="Microsoft.ApplicationInsights.OperationTelemetryExtensions.Stop telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry" RefType="this" />
      </Parameters>
      <Docs>
        <param name="telemetry"><span data-ttu-id="4e796-109">この拡張メソッドを呼び出すのテレメトリ項目オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4e796-109">Telemetry item object that calls this extension method.</span></span></param>
        <summary>
            <span data-ttu-id="4e796-110">製品利用統計情報項目をタイマーを停止し、要求または依存関係の期間を計算する拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="4e796-110">An extension method to telemetry item that stops the timer and computes the duration of the request or dependency.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static void Stop (this Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry telemetry, long timestamp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Stop(class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry telemetry, int64 timestamp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.OperationTelemetryExtensions.Stop(Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Stop (telemetry As OperationTelemetry, timestamp As Long)" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry * int64 -&gt; unit" Usage="Microsoft.ApplicationInsights.OperationTelemetryExtensions.Stop (telemetry, timestamp)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry" RefType="this" />
        <Parameter Name="timestamp" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="telemetry"><span data-ttu-id="4e796-111">この拡張メソッドを呼び出すのテレメトリ項目オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4e796-111">Telemetry item object that calls this extension method.</span></span></param>
        <param name="timestamp"><span data-ttu-id="4e796-112">高解像度のタイムスタンプから<see cref="T:System.Diagnostics.Stopwatch" />です。</span><span class="sxs-lookup"><span data-stu-id="4e796-112">A high-resolution timestamp from <see cref="T:System.Diagnostics.Stopwatch" />.</span></span></param>
        <summary>
            <span data-ttu-id="4e796-113">製品利用統計情報項目をタイマーを停止し、要求または依存関係の期間を計算する拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="4e796-113">An extension method to telemetry item that stops the timer and computes the duration of the request or dependency.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>