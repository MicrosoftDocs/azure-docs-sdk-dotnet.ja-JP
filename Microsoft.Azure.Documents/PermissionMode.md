<Type Name="PermissionMode" FullName="Microsoft.Azure.Documents.PermissionMode">
  <TypeSignature Language="C#" Value="public enum PermissionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PermissionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.PermissionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum PermissionMode" />
  <TypeSignature Language="F#" Value="type PermissionMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary> 
            これらは、作成または置換するためのアクセス許可、 <see cref="T:Microsoft.Azure.Documents.Permission" /> Cosmos DB の Azure サービス内のリソース。
            </summary>
    <remarks>
            アクセス許可リソースでは、アクセスのアクセス許可には特定のリソースにユーザーを関連付けます。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="All" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.PermissionMode All = unsigned int8(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.PermissionMode.All" />
      <MemberSignature Language="VB.NET" Value="All" />
      <MemberSignature Language="F#" Value="All = 2" Usage="Microsoft.Azure.Documents.PermissionMode.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.PermissionMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            すべてのアクセス許可モードはリソースに、フル アクセス (読み取り、挿入、置換および削除) を持つユーザーに提供されます。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="Read" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.PermissionMode Read = unsigned int8(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.PermissionMode.Read" />
      <MemberSignature Language="VB.NET" Value="Read" />
      <MemberSignature Language="F#" Value="Read = 1" Usage="Microsoft.Azure.Documents.PermissionMode.Read" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.PermissionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            読み取りアクセス許可モードでは、リソースへの読み取り専用アクセスを持つユーザーを提供します。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>