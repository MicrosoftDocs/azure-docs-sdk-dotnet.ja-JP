<Type Name="ApplicationLoadMetricInformation" FullName="System.Fabric.Query.ApplicationLoadMetricInformation">
  <TypeSignature Language="C#" Value="public sealed class ApplicationLoadMetricInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationLoadMetricInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationLoadMetricInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationLoadMetricInformation" />
  <TypeSignature Language="F#" Value="type ApplicationLoadMetricInformation = class" />
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
            容量と、アプリケーションのサービスを使用して 1 つのメトリックの現在の負荷に関する情報を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationLoadMetricInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationLoadMetricInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationCapacity">
      <MemberSignature Language="C#" Value="public long ApplicationCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ApplicationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadMetricInformation.ApplicationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.ApplicationCapacity : int64" Usage="System.Fabric.Query.ApplicationLoadMetricInformation.ApplicationCapacity" />
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
            この指標の合計容量を取得します。
            </summary>
        <value>
            このアプリケーションのサービスが使用できるこのメトリックに使用される合計容量。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLoad">
      <MemberSignature Language="C#" Value="public long ApplicationLoad { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ApplicationLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadMetricInformation.ApplicationLoad" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationLoad As Long" />
      <MemberSignature Language="F#" Value="member this.ApplicationLoad : int64" Usage="System.Fabric.Query.ApplicationLoadMetricInformation.ApplicationLoad" />
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
            このメトリックの負荷を取得します。
            </summary>
        <value>
            このアプリケーションのサービスを使用して、合計負荷します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadMetricInformation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Query.ApplicationLoadMetricInformation.Name" />
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
            メトリックの名前を取得します。
            </summary>
        <value>
            メトリックの名前。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReservationCapacity">
      <MemberSignature Language="C#" Value="public long ReservationCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReservationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationLoadMetricInformation.ReservationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReservationCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.ReservationCapacity : int64" Usage="System.Fabric.Query.ApplicationLoadMetricInformation.ReservationCapacity" />
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
            このメトリックの占有容量を取得します。
            </summary>
        <value>
            このアプリケーションのクラスター内で予約されている容量の振り替えさせていただきます。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationLoadMetricInformation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationLoadMetricInformation.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            詳細をかなり印刷<see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" />です。
            </para>
        </summary>
        <returns><see cref="T:System.Fabric.Query.ApplicationLoadMetricInformation" /> の文字列形式。</returns>
        <remarks>To be added.</remarks>
        <example>
            LoadMetricName: Metric1 ReservationCapacity: 10 ApplicationCapacity: 10 ApplicationLoad: 2
            </example>
      </Docs>
    </Member>
  </Members>
</Type>