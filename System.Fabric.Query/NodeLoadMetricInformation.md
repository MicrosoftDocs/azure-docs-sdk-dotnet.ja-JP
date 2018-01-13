<Type Name="NodeLoadMetricInformation" FullName="System.Fabric.Query.NodeLoadMetricInformation">
  <TypeSignature Language="C#" Value="public sealed class NodeLoadMetricInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeLoadMetricInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.NodeLoadMetricInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeLoadMetricInformation" />
  <TypeSignature Language="F#" Value="type NodeLoadMetricInformation = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>ノード上の特定のメトリックの読み込み情報を格納するデータ構造を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeLoadMetricInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.NodeLoadMetricInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Query.NodeLoadMetricInformation" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferedNodeCapacityRemaining">
      <MemberSignature Language="C#" Value="public double BufferedNodeCapacityRemaining { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 BufferedNodeCapacityRemaining" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.BufferedNodeCapacityRemaining" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BufferedNodeCapacityRemaining As Double" />
      <MemberSignature Language="F#" Value="member this.BufferedNodeCapacityRemaining : double" Usage="System.Fabric.Query.NodeLoadMetricInformation.BufferedNodeCapacityRemaining" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>NodeBufferPercentage によって予約されていないいる残りの容量を示す値を取得します。</para>
        </summary>
        <value>
          <para>この指標ノード上のない NodeBufferPercentage によって予約されている残りの容量。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentNodeLoad">
      <MemberSignature Language="C#" Value="public double CurrentNodeLoad { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 CurrentNodeLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.CurrentNodeLoad" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentNodeLoad As Double" />
      <MemberSignature Language="F#" Value="member this.CurrentNodeLoad : double" Usage="System.Fabric.Query.NodeLoadMetricInformation.CurrentNodeLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>&gt;メトリックのノードで、現在の負荷を取得します。</para>
        </summary>
        <value>
          <para>メトリックのノードの現在の負荷。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCapacityViolation">
      <MemberSignature Language="C#" Value="public bool IsCapacityViolation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsCapacityViolation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.IsCapacityViolation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsCapacityViolation As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsCapacityViolation : bool" Usage="System.Fabric.Query.NodeLoadMetricInformation.IsCapacityViolation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>指定したノードのメトリックの容量違反があるかどうかを示す値を取得します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword> ; 指定したノードのメトリックの容量違反がある場合は、それ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Query.NodeLoadMetricInformation.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>メトリックの名前を取得します。</para>
        </summary>
        <value>
          <para>メトリックの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeBufferedCapacity">
      <MemberSignature Language="C#" Value="public long NodeBufferedCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeBufferedCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.NodeBufferedCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeBufferedCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.NodeBufferedCapacity : int64" Usage="System.Fabric.Query.NodeLoadMetricInformation.NodeBufferedCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>NodeBufferPercentage によって予約されていないいる容量を示す値を取得します。</para>
        </summary>
        <value>
          <para>この指標ノード上のない NodeBufferPercentage によって予約されている容量です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeCapacity">
      <MemberSignature Language="C#" Value="public long NodeCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.NodeCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.NodeCapacity : int64" Usage="System.Fabric.Query.NodeLoadMetricInformation.NodeCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ノードのメトリックの総容量を取得します。</para>
        </summary>
        <value>
          <para>メトリックのノードの合計容量。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeCapacityRemaining">
      <MemberSignature Language="C#" Value="public double NodeCapacityRemaining { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 NodeCapacityRemaining" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.NodeCapacityRemaining" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeCapacityRemaining As Double" />
      <MemberSignature Language="F#" Value="member this.NodeCapacityRemaining : double" Usage="System.Fabric.Query.NodeLoadMetricInformation.NodeCapacityRemaining" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>メトリックのノード上の残りの容量を取得します。</para>
        </summary>
        <value>
          <para>ノード上のメトリックの残りの容量</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeLoad">
      <MemberSignature Language="C#" Value="public long NodeLoad { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.NodeLoad" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeLoad As Long" />
      <MemberSignature Language="F#" Value="member this.NodeLoad : int64" Usage="System.Fabric.Query.NodeLoadMetricInformation.NodeLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>メトリックのノードで、現在の負荷を取得します。</para>
          <para>
            Service Fabric の代わりにこのパラメーターが廃止される予定の将来のリリースで<see cref="P:System.Fabric.Query.NodeLoadMetricInformation.CurrentNodeLoad" />です。
            </para>
        </summary>
        <value>
          <para>メトリックのノードの現在の負荷。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeRemainingBufferedCapacity">
      <MemberSignature Language="C#" Value="public long NodeRemainingBufferedCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeRemainingBufferedCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.NodeRemainingBufferedCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeRemainingBufferedCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.NodeRemainingBufferedCapacity : int64" Usage="System.Fabric.Query.NodeLoadMetricInformation.NodeRemainingBufferedCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>NodeBufferPercentage によって予約されていないいる残りの容量を示す値を取得します。</para>
          <para>
            Service Fabric の代わりにこのパラメーターが廃止される予定の将来のリリースで<see cref="P:System.Fabric.Query.NodeLoadMetricInformation.BufferedNodeCapacityRemaining" />です。
            </para>
        </summary>
        <value>
          <para>この指標ノード上のない NodeBufferPercentage によって予約されている残りの容量。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeRemainingCapacity">
      <MemberSignature Language="C#" Value="public long NodeRemainingCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeRemainingCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadMetricInformation.NodeRemainingCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeRemainingCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.NodeRemainingCapacity : int64" Usage="System.Fabric.Query.NodeLoadMetricInformation.NodeRemainingCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>メトリックのノード上の残りの容量を取得します。</para>
          <para>
            Service Fabric の代わりにこのパラメーターが廃止される予定の将来のリリースで<see cref="P:System.Fabric.Query.NodeLoadMetricInformation.NodeCapacityRemaining" />です。
            </para>
        </summary>
        <value>
          <para>ノード上のメトリックの残りの容量</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>