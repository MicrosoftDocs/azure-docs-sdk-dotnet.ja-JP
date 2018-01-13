<Type Name="ElevationLevel" FullName="Microsoft.Azure.Batch.Protocol.Models.ElevationLevel">
  <TypeSignature Language="C#" Value="public enum ElevationLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ElevationLevel extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ElevationLevel" />
  <TypeSignature Language="VB.NET" Value="Public Enum ElevationLevel" />
  <TypeSignature Language="F#" Value="type ElevationLevel = " />
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
            <span data-ttu-id="21045-101">ElevationLevel の値を定義します。</span><span class="sxs-lookup"><span data-stu-id="21045-101">Defines values for ElevationLevel.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Admin">
      <MemberSignature Language="C#" Value="Admin" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ElevationLevel Admin = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ElevationLevel.Admin" />
      <MemberSignature Language="VB.NET" Value="Admin" />
      <MemberSignature Language="F#" Value="Admin = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.ElevationLevel.Admin" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="admin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ElevationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="21045-102">このユーザーは、昇格されたアクセス権を持つユーザーで完全な管理者アクセス許可で操作を行います。</span><span class="sxs-lookup"><span data-stu-id="21045-102">The user is a user with elevated access and operates with full Administrator permissions.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NonAdmin">
      <MemberSignature Language="C#" Value="NonAdmin" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ElevationLevel NonAdmin = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ElevationLevel.NonAdmin" />
      <MemberSignature Language="VB.NET" Value="NonAdmin" />
      <MemberSignature Language="F#" Value="NonAdmin = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.ElevationLevel.NonAdmin" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="nonadmin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ElevationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="21045-103">ユーザーは、管理者特権でのアクセス権のない標準ユーザーです。</span><span class="sxs-lookup"><span data-stu-id="21045-103">The user is a standard user without elevated access.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>