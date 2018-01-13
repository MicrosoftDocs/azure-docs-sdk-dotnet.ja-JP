<Type Name="ChaosEvent" FullName="System.Fabric.Chaos.DataStructures.ChaosEvent">
  <TypeSignature Language="C#" Value="public abstract class ChaosEvent : System.Fabric.ByteSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract serializable beforefieldinit ChaosEvent extends System.Fabric.ByteSerializable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ChaosEvent&#xA;Inherits ByteSerializable" />
  <TypeSignature Language="F#" Value="type ChaosEvent = class&#xA;    inherit ByteSerializable" />
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
            これは、カオスにより生成されるイベントのすべてのさまざまな種類の基本クラス
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosEvent.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="System.Fabric.Chaos.DataStructures.ChaosEvent.Kind" />
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
          <para>ChaosEvent の種類について説明します。</para>
        </summary>
        <value>
          <para>返します<see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />派生 ChaosEvent の種類</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public abstract void Read (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Read(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosEvent.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Read (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="override this.Read : System.IO.BinaryReader -&gt; unit" Usage="chaosEvent.Read br" />
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
        <param name="br">BinaryReader オブジェクト</param>
        <summary>
            このメソッドが渡された派生クラスの実装の上に
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadInheritedMembers">
      <MemberSignature Language="C#" Value="protected void ReadInheritedMembers (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ReadInheritedMembers(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosEvent.ReadInheritedMembers(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ReadInheritedMembers (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="member this.ReadInheritedMembers : System.IO.BinaryReader -&gt; unit" Usage="chaosEvent.ReadInheritedMembers br" />
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
        <param name="br">BinaryReader オブジェクト</param>
        <summary>
            このメソッドはバイトからの継承されたメンバーを変換する派生クラスから呼び出されます
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeStampUtc">
      <MemberSignature Language="C#" Value="public DateTime TimeStampUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime TimeStampUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosEvent.TimeStampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeStampUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.TimeStampUtc : DateTime" Usage="System.Fabric.Chaos.DataStructures.ChaosEvent.TimeStampUtc" />
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
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            イベントが発生したときの日付と時刻
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToBytes">
      <MemberSignature Language="C#" Value="public override byte[] ToBytes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance unsigned int8[] ToBytes() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosEvent.ToBytes" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToBytes () As Byte()" />
      <MemberSignature Language="F#" Value="override this.ToBytes : unit -&gt; byte[]" Usage="chaosEvent.ToBytes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このオーバーライド Chaos イベント オブジェクトをバイト配列に変換するために、イベントの種類を記述して、まずし、派生クラスの書き込みメソッドを呼び出します
            </summary>
        <returns>バイト配列</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosEvent.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="chaosEvent.ToString " />
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
            クラスの文字列表現を返します
            </summary>
        <returns>String オブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public abstract void Write (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosEvent.Write(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Write (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="override this.Write : System.IO.BinaryWriter -&gt; unit" Usage="chaosEvent.Write bw" />
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
        <param name="bw">BinaryWriter オブジェクト</param>
        <summary>
            このメソッドは実装の派生クラスに渡されます
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteInheritedMembers">
      <MemberSignature Language="C#" Value="protected void WriteInheritedMembers (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void WriteInheritedMembers(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosEvent.WriteInheritedMembers(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub WriteInheritedMembers (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="member this.WriteInheritedMembers : System.IO.BinaryWriter -&gt; unit" Usage="chaosEvent.WriteInheritedMembers bw" />
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
        <param name="bw">BinaryWriter オブジェクト</param>
        <summary>
            このメソッドは継承されたメンバーをバイトに変換する派生クラスから呼び出されます
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>