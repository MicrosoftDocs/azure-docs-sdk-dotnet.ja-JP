<Type Name="RestorePolicy" FullName="Microsoft.ServiceFabric.Data.RestorePolicy">
  <TypeSignature Language="C#" Value="public enum RestorePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RestorePolicy extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.RestorePolicy" />
  <TypeSignature Language="VB.NET" Value="Public Enum RestorePolicy" />
  <TypeSignature Language="F#" Value="type RestorePolicy = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            復元操作のポリシーです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Force">
      <MemberSignature Language="C#" Value="Force" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Data.RestorePolicy Force = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Data.RestorePolicy.Force" />
      <MemberSignature Language="VB.NET" Value="Force" />
      <MemberSignature Language="F#" Value="Force = 1" Usage="Microsoft.ServiceFabric.Data.RestorePolicy.Force" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.RestorePolicy</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            状態をバックアップするかどうかをチェックしません、現在の状態は、復元中です。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Safe">
      <MemberSignature Language="C#" Value="Safe" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Data.RestorePolicy Safe = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Data.RestorePolicy.Safe" />
      <MemberSignature Language="VB.NET" Value="Safe" />
      <MemberSignature Language="F#" Value="Safe = 0" Usage="Microsoft.ServiceFabric.Data.RestorePolicy.Safe" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.RestorePolicy</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            復元されるバックアップ状態が現在の状態の前であることを確認します。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>