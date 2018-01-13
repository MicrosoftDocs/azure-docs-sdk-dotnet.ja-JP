<Type Name="ExceptionHandledAt" FullName="Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt">
  <TypeSignature Language="C#" Value="public enum ExceptionHandledAt" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ExceptionHandledAt extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt" />
  <TypeSignature Language="VB.NET" Value="Public Enum ExceptionHandledAt" />
  <TypeSignature Language="F#" Value="type ExceptionHandledAt = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Use custom properties to report exception handling layer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            場合に識別する ExceptionTelemetry でこの列挙を使用し、例外が処理します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Platform">
      <MemberSignature Language="C#" Value="Platform" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt Platform = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt.Platform" />
      <MemberSignature Language="VB.NET" Value="Platform" />
      <MemberSignature Language="F#" Value="Platform = 2" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt.Platform" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            例外は、一部のプラットフォーム ハンドラーによって処理されていました。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unhandled">
      <MemberSignature Language="C#" Value="Unhandled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt Unhandled = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt.Unhandled" />
      <MemberSignature Language="VB.NET" Value="Unhandled" />
      <MemberSignature Language="F#" Value="Unhandled = 0" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt.Unhandled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            例外は処理されませんでした。 アプリケーションがクラッシュしました。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="UserCode">
      <MemberSignature Language="C#" Value="UserCode" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt UserCode = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt.UserCode" />
      <MemberSignature Language="VB.NET" Value="UserCode" />
      <MemberSignature Language="F#" Value="UserCode = 1" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt.UserCode" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            ユーザー コードで例外が処理されました。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>