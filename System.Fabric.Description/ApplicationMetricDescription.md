<Type Name="ApplicationMetricDescription" FullName="System.Fabric.Description.ApplicationMetricDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationMetricDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationMetricDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationMetricDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationMetricDescription" />
  <TypeSignature Language="F#" Value="type ApplicationMetricDescription = class" />
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
            1 つのメトリックの容量のアプリケーションを指定します。
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="T:System.Fabric.Description.ApplicationDescription" />
    <altmember cref="T:System.Fabric.Description.ApplicationUpdateDescription" />
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationMetricDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationMetricDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNodeCapacity">
      <MemberSignature Language="C#" Value="public long MaximumNodeCapacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaximumNodeCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationMetricDescription.MaximumNodeCapacity" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumNodeCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.MaximumNodeCapacity : int64 with get, set" Usage="System.Fabric.Description.ApplicationMetricDescription.MaximumNodeCapacity" />
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
            取得または Service Fabric アプリケーションの最大ノード容量を設定します。
            </summary>
        <value>
          <para>
            1 つのノードでこのアプリケーションのインスタンスの最大負荷を指定します。
            ノードの容量がこの値よりも大きい場合でも、この値を各ノードで、アプリケーション内のサービスでの合計の負荷が Service Fabric に制限されます。
            </para>
          <para>0 に設定すると、この指標の容量は無制限に各ノードにします。</para>
          <para>
            アプリケーションの容量を持つ新しいアプリケーションを作成する定義されている場合の製品<see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />し、この値よりも小さいか等しい必ず<see cref="P:System.Fabric.Description.ApplicationMetricDescription.TotalApplicationCapacity" />です。
            </para>
          <para>
            アプリケーションの性能の製品の既存のアプリケーションを更新中に<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />し、この値よりも小さいか等しい必ず<see cref="P:System.Fabric.Description.ApplicationMetricDescription.TotalApplicationCapacity" />です。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationMetricDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="System.Fabric.Description.ApplicationMetricDescription.Name" />
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
            取得またはメトリックの名前を設定します。
            </summary>
        <value>
            メトリックの名前。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeReservationCapacity">
      <MemberSignature Language="C#" Value="public long NodeReservationCapacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NodeReservationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationMetricDescription.NodeReservationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeReservationCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.NodeReservationCapacity : int64 with get, set" Usage="System.Fabric.Description.ApplicationMetricDescription.NodeReservationCapacity" />
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
            取得または Service Fabric アプリケーションのノードの予約容量を設定します。
            </summary>
        <value>
          <para>
            このアプリケーションのインスタンスである必要がノードで予約されているメトリック負荷の量を指定します。
            場合<see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />が指定されて、これらの値の積は、アプリケーションのクラスター内で予約された容量になります。
            </para>
          <para>
            かどうかゼロに設定すると、容量は予約されていません、この指標です。
            </para>
          <para>
            アプリケーションの性能を設定するときに (<see cref="T:System.Fabric.Description.ApplicationDescription" />) アプリケーションの性能を更新するときに、または ((<see cref="T:System.Fabric.Description.ApplicationUpdateDescription" />) よりも小さいか等しいを値として使用することがあります<see cref="P:System.Fabric.Description.ApplicationMetricDescription.MaximumNodeCapacity" />メトリックごとにします。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalApplicationCapacity">
      <MemberSignature Language="C#" Value="public long TotalApplicationCapacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalApplicationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationMetricDescription.TotalApplicationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalApplicationCapacity As Long" />
      <MemberSignature Language="F#" Value="member this.TotalApplicationCapacity : int64 with get, set" Usage="System.Fabric.Description.ApplicationMetricDescription.TotalApplicationCapacity" />
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
            取得または Service Fabric アプリケーションの指標合計容量を設定します。
            </summary>
        <value>
          <para>
            クラスターでは、このアプリケーションの指標合計容量を指定します。
            Service Fabric は、この値にアプリケーション内でサービスの負荷の合計を制限しようとしています。
            </para>
          <para>
            アプリケーションの容量を持つ新しいアプリケーションを作成する定義されている場合の製品<see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />と<see cref="P:System.Fabric.Description.ApplicationMetricDescription.MaximumNodeCapacity" />よりも小さいか、この値に等しいを常にする必要があります。
            </para>
          <para>
            アプリケーションの容量を持つ新しいアプリケーションを作成する定義されている場合の製品<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />と<see cref="P:System.Fabric.Description.ApplicationMetricDescription.MaximumNodeCapacity" />よりも小さいか、この値に等しいを常にする必要があります。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>