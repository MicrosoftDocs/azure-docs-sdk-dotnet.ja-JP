<Type Name="ChaosReportFilter" FullName="System.Fabric.Chaos.DataStructures.ChaosReportFilter">
  <TypeSignature Language="C#" Value="public sealed class ChaosReportFilter : System.Fabric.ByteSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ChaosReportFilter extends System.Fabric.ByteSerializable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.ChaosReportFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ChaosReportFilter&#xA;Inherits ByteSerializable" />
  <TypeSignature Language="F#" Value="type ChaosReportFilter = class&#xA;    inherit ByteSerializable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.ByteSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="074c9-101">興味深い ChaosEvent に含めるのかを選択するフィルターを表す、<see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" /></span><span class="sxs-lookup"><span data-stu-id="074c9-101">Represents the filter to choose the interesting ChaosEvent's to include in the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" /></span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosReportFilter (DateTime startTimeUtc, DateTime endTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime startTimeUtc, valuetype System.DateTime endTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosReportFilter.#ctor(System.DateTime,System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startTimeUtc As DateTime, endTimeUtc As DateTime)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosReportFilter : DateTime * DateTime -&gt; System.Fabric.Chaos.DataStructures.ChaosReportFilter" Usage="new System.Fabric.Chaos.DataStructures.ChaosReportFilter (startTimeUtc, endTimeUtc)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTimeUtc" Type="System.DateTime" />
        <Parameter Name="endTimeUtc" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="startTimeUtc"></param>
        <param name="endTimeUtc"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EndTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosReportFilter.EndTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTimeUtc : DateTime" Usage="System.Fabric.Chaos.DataStructures.ChaosReportFilter.EndTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override void Read (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Read(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosReportFilter.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Read (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="override this.Read : System.IO.BinaryReader -&gt; unit" Usage="chaosReportFilter.Read br" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="br" Type="System.IO.BinaryReader" />
      </Parameters>
      <Docs>
        <param name="br"><span data-ttu-id="074c9-102">BinaryReader オブジェクト</span><span class="sxs-lookup"><span data-stu-id="074c9-102">A BinaryReader object</span></span></param>
        <summary>
            <span data-ttu-id="074c9-103">バイト配列から、このオブジェクトの状態を読み取ります。</span><span class="sxs-lookup"><span data-stu-id="074c9-103">Reads the state of this object from byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime StartTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosReportFilter.StartTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTimeUtc : DateTime" Usage="System.Fabric.Chaos.DataStructures.ChaosReportFilter.StartTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosReportFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="chaosReportFilter.ToString " />
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
            <span data-ttu-id="074c9-104">Chaos レポート オブジェクトの文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="074c9-104">Gets a string representation of the chaos report object.</span></span>
            </summary>
        <returns><span data-ttu-id="074c9-105">Chaos の状態のオブジェクトの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="074c9-105">A string representation of the chaos status object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosReportFilter.Write(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="override this.Write : System.IO.BinaryWriter -&gt; unit" Usage="chaosReportFilter.Write bw" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bw" Type="System.IO.BinaryWriter" />
      </Parameters>
      <Docs>
        <param name="bw"><span data-ttu-id="074c9-106">BinaryWriter オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="074c9-106">A BinaryWriter object.</span></span></param>
        <summary>
            <span data-ttu-id="074c9-107">このオブジェクトの状態をバイト配列に書き込みます。</span><span class="sxs-lookup"><span data-stu-id="074c9-107">Writes the state of this object into a byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>