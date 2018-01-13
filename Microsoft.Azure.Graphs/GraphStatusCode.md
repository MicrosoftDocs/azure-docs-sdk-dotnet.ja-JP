<Type Name="GraphStatusCode" FullName="Microsoft.Azure.Graphs.GraphStatusCode">
  <TypeSignature Language="C#" Value="public enum GraphStatusCode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed GraphStatusCode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.GraphStatusCode" />
  <TypeSignature Language="VB.NET" Value="Public Enum GraphStatusCode" />
  <TypeSignature Language="F#" Value="type GraphStatusCode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
    <AssemblyVersion>1.14.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            グラフのライブラリによってスローされた例外に関連付けられているエラー コードです。
            RFC: http://tinkerpop.apache.org/docs/current/dev/provider/#_graph_driver_provider_requirements
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Authenticate">
      <MemberSignature Language="C#" Value="Authenticate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode Authenticate = int32(407)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.Authenticate" />
      <MemberSignature Language="VB.NET" Value="Authenticate" />
      <MemberSignature Language="F#" Value="Authenticate = 407" Usage="Microsoft.Azure.Graphs.GraphStatusCode.Authenticate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>407</MemberValue>
      <Docs>
        <summary>
            サーバーからその要求を認証するためのクライアントのチャレンジです。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="InvalidRequestArguments">
      <MemberSignature Language="C#" Value="InvalidRequestArguments" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode InvalidRequestArguments = int32(499)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.InvalidRequestArguments" />
      <MemberSignature Language="VB.NET" Value="InvalidRequestArguments" />
      <MemberSignature Language="F#" Value="InvalidRequestArguments = 499" Usage="Microsoft.Azure.Graphs.GraphStatusCode.InvalidRequestArguments" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>499</MemberValue>
      <Docs>
        <summary>
            要求メッセージが解析可能なが、メッセージで指定された引数が競合しているか不完全です。 メッセージ形式を確認して、要求を再試行してください。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="MalformedRequest">
      <MemberSignature Language="C#" Value="MalformedRequest" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode MalformedRequest = int32(498)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.MalformedRequest" />
      <MemberSignature Language="VB.NET" Value="MalformedRequest" />
      <MemberSignature Language="F#" Value="MalformedRequest = 498" Usage="Microsoft.Azure.Graphs.GraphStatusCode.MalformedRequest" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>498</MemberValue>
      <Docs>
        <summary>
            要求メッセージ形式が正しくありませんそれを解析できませんでしたまったくまたは Gremlin サーバーでしたを適切にルーティングが処理されるよう、"op"コードは認識されませんでした。 メッセージ形式を確認して、要求を再試行してください。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NoContent">
      <MemberSignature Language="C#" Value="NoContent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode NoContent = int32(204)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.NoContent" />
      <MemberSignature Language="VB.NET" Value="NoContent" />
      <MemberSignature Language="F#" Value="NoContent = 204" Usage="Microsoft.Azure.Graphs.GraphStatusCode.NoContent" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>204</MemberValue>
      <Docs>
        <summary>
            サーバーは要求を処理するが、(たとえば、反復子要素を持たない) を返す結果はありません - このストリームの残りのメッセージはありません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PartialContent">
      <MemberSignature Language="C#" Value="PartialContent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode PartialContent = int32(206)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.PartialContent" />
      <MemberSignature Language="VB.NET" Value="PartialContent" />
      <MemberSignature Language="F#" Value="PartialContent = 206" Usage="Microsoft.Azure.Graphs.GraphStatusCode.PartialContent" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>206</MemberValue>
      <Docs>
        <summary>
            サーバーは、一部のコンテンツを正常に返されるが、詳細については、到着 - をストリームの末尾を示すために、成功を待機するストリーム。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RateLimiting">
      <MemberSignature Language="C#" Value="RateLimiting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode RateLimiting = int32(429)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.RateLimiting" />
      <MemberSignature Language="VB.NET" Value="RateLimiting" />
      <MemberSignature Language="F#" Value="RateLimiting = 429" Usage="Microsoft.Azure.Graphs.GraphStatusCode.RateLimiting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>429</MemberValue>
      <Docs>
        <summary>
            クォータを超過を計算します。 (HTTP 状態コード)
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ScriptEvaluationError">
      <MemberSignature Language="C#" Value="ScriptEvaluationError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode ScriptEvaluationError = int32(597)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.ScriptEvaluationError" />
      <MemberSignature Language="VB.NET" Value="ScriptEvaluationError" />
      <MemberSignature Language="F#" Value="ScriptEvaluationError = 597" Usage="Microsoft.Azure.Graphs.GraphStatusCode.ScriptEvaluationError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>597</MemberValue>
      <Docs>
        <summary>
            処理のために送信するスクリプトは、エラーが発生 ScriptEngine で評価されを処理できませんでした。 構文エラーまたはその他の問題のために送信するスクリプトを確認し、再送信します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ServerError">
      <MemberSignature Language="C#" Value="ServerError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode ServerError = int32(500)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.ServerError" />
      <MemberSignature Language="VB.NET" Value="ServerError" />
      <MemberSignature Language="F#" Value="ServerError = 500" Usage="Microsoft.Azure.Graphs.GraphStatusCode.ServerError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>500</MemberValue>
      <Docs>
        <summary>
            要求が処理されていることを防止する一般的なサーバー エラーが発生しました。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ServerSerializationError">
      <MemberSignature Language="C#" Value="ServerSerializationError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode ServerSerializationError = int32(599)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.ServerSerializationError" />
      <MemberSignature Language="VB.NET" Value="ServerSerializationError" />
      <MemberSignature Language="F#" Value="ServerSerializationError = 599" Usage="Microsoft.Azure.Graphs.GraphStatusCode.ServerSerializationError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>599</MemberValue>
      <Docs>
        <summary>
            サーバーは、要求で指定されたスクリプトから返されたオブジェクトをシリアル化できるでした。 いずれかにより、オブジェクトが何か Gremlin サーバーは、スクリプト内で処理したり、マッパーのシリアル化クラスを Gremlin サーバーにインストールに変換します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="ServerTimeout" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode ServerTimeout = int32(598)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="ServerTimeout" />
      <MemberSignature Language="F#" Value="ServerTimeout = 598" Usage="Microsoft.Azure.Graphs.GraphStatusCode.ServerTimeout" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>598</MemberValue>
      <Docs>
        <summary>
            サーバーは要求のタイムアウト設定のいずれかを超えたため、応答またはすべての応答しませんでした部分的にのみ、したがって可能性があります。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Success">
      <MemberSignature Language="C#" Value="Success" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode Success = int32(200)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.Success" />
      <MemberSignature Language="VB.NET" Value="Success" />
      <MemberSignature Language="F#" Value="Success = 200" Usage="Microsoft.Azure.Graphs.GraphStatusCode.Success" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>200</MemberValue>
      <Docs>
        <summary>
            サーバーが正常に完了する要求を処理 - このストリームの残りのメッセージはありません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unauthorized">
      <MemberSignature Language="C#" Value="Unauthorized" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode Unauthorized = int32(401)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.Unauthorized" />
      <MemberSignature Language="VB.NET" Value="Unauthorized" />
      <MemberSignature Language="F#" Value="Unauthorized = 401" Usage="Microsoft.Azure.Graphs.GraphStatusCode.Unauthorized" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>401</MemberValue>
      <Docs>
        <summary>
            要求は、要求元のユーザーがへのアクセスがありませんリソースにアクセスしようとしました。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>