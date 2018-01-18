<Type Name="StoppedEvent" FullName="System.Fabric.Chaos.DataStructures.StoppedEvent">
  <TypeSignature Language="C#" Value="public sealed class StoppedEvent : System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit StoppedEvent extends System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.StoppedEvent" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StoppedEvent&#xA;Inherits ChaosEvent" />
  <TypeSignature Language="F#" Value="type StoppedEvent = class&#xA;    inherit ChaosEvent" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Chaos.DataStructures.ChaosEvent</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="81193-101">何らかの理由により Chaos が停止しているときに作成される Chaos イベントを表します。</span><span class="sxs-lookup"><span data-stu-id="81193-101">Represents the Chaos event that is created when Chaos is stopped for some reason.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override void Read (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Read(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.StoppedEvent.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Read (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="override this.Read : System.IO.BinaryReader -&gt; unit" Usage="stoppedEvent.Read br" />
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
        <param name="br"><span data-ttu-id="81193-102">BinaryReader オブジェクト</span><span class="sxs-lookup"><span data-stu-id="81193-102">A BinaryReader object</span></span></param>
        <summary>
            <span data-ttu-id="81193-103">バイト配列から、このオブジェクトの状態を読み取ります。</span><span class="sxs-lookup"><span data-stu-id="81193-103">Reads the state of this object from byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.EndOfStreamException"><span data-ttu-id="81193-104">ストリームの末尾に到達しました。</span><span class="sxs-lookup"><span data-stu-id="81193-104">The end of the stream is reached.</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.StoppedEvent.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string" Usage="System.Fabric.Chaos.DataStructures.StoppedEvent.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81193-105">停止の理由を取得します。</span><span class="sxs-lookup"><span data-stu-id="81193-105">Gets the reason for stopping.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.StoppedEvent.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="stoppedEvent.ToString " />
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
            <span data-ttu-id="81193-106">停止イベントの文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="81193-106">Gets a string representation of the stopped event.</span></span>
            </summary>
        <returns><span data-ttu-id="81193-107">停止イベントの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="81193-107">A string representation of the stopped event.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.StoppedEvent.Write(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="override this.Write : System.IO.BinaryWriter -&gt; unit" Usage="stoppedEvent.Write bw" />
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
        <param name="bw"><span data-ttu-id="81193-108">BinaryWriter オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="81193-108">A BinaryWriter object.</span></span></param>
        <summary>
            <span data-ttu-id="81193-109">このオブジェクトの状態をバイト配列に書き込みます。</span><span class="sxs-lookup"><span data-stu-id="81193-109">Writes the state of this object into a byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.IOException"><span data-ttu-id="81193-110">I/O エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="81193-110">An I/O error occurs.</span></span> </exception>
      </Docs>
    </Member>
  </Members>
</Type>