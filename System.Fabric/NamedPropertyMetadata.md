<Type Name="NamedPropertyMetadata" FullName="System.Fabric.NamedPropertyMetadata">
  <TypeSignature Language="C#" Value="public sealed class NamedPropertyMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamedPropertyMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NamedPropertyMetadata" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamedPropertyMetadata" />
  <TypeSignature Language="F#" Value="type NamedPropertyMetadata = class" />
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
      <para>関連付けられているメタデータ、<see cref="T:System.Fabric.NamedProperty" />プロパティの名前を含むです。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CustomTypeId">
      <MemberSignature Language="C#" Value="public string CustomTypeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomTypeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.CustomTypeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomTypeId As String" />
      <MemberSignature Language="F#" Value="member this.CustomTypeId : string" Usage="System.Fabric.NamedPropertyMetadata.CustomTypeId" />
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
          <para>カスタム型の id を取得します。</para>
        </summary>
        <value>
          <para>カスタム型の id です。</para>
        </value>
        <remarks>
          <para>このプロパティを使用して、ユーザーは、プロパティの値の型のタグを付けることです。 このプロパティの一般的なユース ケースは、以下のようです。 構成と呼ばれるプロパティがあると仮定します。 このプロパティの値は、最後に更新されたユーザーのプロパティによって、JSON または XML を指定できます。 このシナリオでは、更新は、プロパティの型をプロパティのコンシューマーに通信するためにカスタム型の id プロパティを使用できます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedUtc">
      <MemberSignature Language="C#" Value="public DateTime LastModifiedUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastModifiedUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.LastModifiedUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastModifiedUtc : DateTime" Usage="System.Fabric.NamedPropertyMetadata.LastModifiedUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>プロパティが最後に変更されたときに取得します。 書き込み操作のみを更新するには、このフィールドとなります。</para>
        </summary>
        <value>
          <para>前回プロパティが変更された UTC です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parent">
      <MemberSignature Language="C#" Value="public Uri Parent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Parent" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.Parent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parent As Uri" />
      <MemberSignature Language="F#" Value="member this.Parent : Uri" Usage="System.Fabric.NamedPropertyMetadata.Parent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービス ファブリック名プロパティの親の名前を取得します。 プロパティが存在する名前空間/テーブルと考える可能性があります。</para>
        </summary>
        <value>
          <para>サービス ファブリック名プロパティの親の名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyName">
      <MemberSignature Language="C#" Value="public string PropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PropertyName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.PropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PropertyName : string" Usage="System.Fabric.NamedPropertyMetadata.PropertyName" />
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
          <para>プロパティの名前を取得します。 キー値のペアのキーと考える可能性があります。</para>
        </summary>
        <value>
          <para>プロパティ名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="System.Fabric.NamedPropertyMetadata.SequenceNumber" />
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
          <para>プロパティのバージョンを取得します。 プロパティが変更されるたびにそのシーケンス番号は増加します。</para>
        </summary>
        <value>
          <para>プロパティのバージョンです。</para>
        </value>
        <remarks>
          <para>常に増やすには、シーケンス番号が保証されます。 ただし、増加は単調できない可能性があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeId">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyTypeId TypeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyTypeId TypeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.TypeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TypeId As PropertyTypeId" />
      <MemberSignature Language="F#" Value="member this.TypeId : System.Fabric.PropertyTypeId" Usage="System.Fabric.NamedPropertyMetadata.TypeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PropertyTypeId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>プロパティの値が、バイナリ、かどうかを示します<see cref="T:System.Int64" />、 <see cref="T:System.Double" />、<see cref="T:System.String" />または<see cref="T:System.Guid" />です。 このフィールドの一般的な用途を使用する型を判断する、<see cref="M:System.Fabric.NamedProperty.GetValue``1" />です。</para>
        </summary>
        <value>
          <para>プロパティのプロパティの型。</para>
        </value>
        <remarks>
          <para>すべての Service Fabric の列挙には、予約済みの無効な値があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValueSize">
      <MemberSignature Language="C#" Value="public int ValueSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ValueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.ValueSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValueSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ValueSize : int" Usage="System.Fabric.NamedPropertyMetadata.ValueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>シリアル化されたプロパティ値の長さを示します。</para>
        </summary>
        <value>
          <para>シリアル化されたプロパティの値の長さ。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>