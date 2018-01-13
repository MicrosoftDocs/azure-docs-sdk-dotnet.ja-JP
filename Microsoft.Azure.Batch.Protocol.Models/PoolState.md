<Type Name="PoolState" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolState">
  <TypeSignature Language="C#" Value="public enum PoolState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PoolState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolState" />
  <TypeSignature Language="VB.NET" Value="Public Enum PoolState" />
  <TypeSignature Language="F#" Value="type PoolState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            PoolState の値を定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.PoolState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.PoolState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolState.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="active")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            プールは、コンピューティング ノードの可用性の対象のタスクを実行できるようにします。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.PoolState Deleting = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.PoolState.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolState.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="deleting")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            ユーザーが、プールが削除されることを要求しましたが、削除操作がまだ完了していません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Upgrading">
      <MemberSignature Language="C#" Value="Upgrading" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.PoolState Upgrading = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.PoolState.Upgrading" />
      <MemberSignature Language="VB.NET" Value="Upgrading" />
      <MemberSignature Language="F#" Value="Upgrading = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolState.Upgrading" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="upgrading")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            ユーザーが、プールのノードのオペレーティング システムをアップグレードすることを要求しましたが、アップグレード操作がまだ完了していない (つまり、プール内のいくつかのノードがまだアップグレードされていない)。 アップグレードすると、プールが (容量が減り) のタスクを実行することができますは保証されません。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>